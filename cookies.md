# Cookies

Cookies sind kleine Dateien, die von einer Webseite auf dem Computer des Benutzers gespeichert werden. Sie dienen dazu, Informationen über den Benutzer zu speichern und zu verfolgen. Es gibt verschiedene Arten von Cookies:

1. **Session-Cookies**: Diese Cookies werden gelöscht, sobald der Benutzer seinen Browser schließt. Sie werden verwendet, um temporäre Informationen zu speichern, wie z.B. Artikel in einem Einkaufswagen.

2. **Persistent Cookies**: Diese Cookies bleiben auf dem Computer des Benutzers, bis sie ablaufen oder vom Benutzer gelöscht werden. Sie werden verwendet, um Informationen über den Benutzer über mehrere Browsersitzungen hinweg zu speichern, wie z.B. Präferenzen oder Anmeldeinformationen.

3. **Third-Party-Cookies**: Diese Cookies werden von Dritten, wie z.B. Werbenetzwerken, gesetzt und können verwendet werden, um den Benutzer über verschiedene Webseiten hinweg zu verfolgen.

Hier ist ein einfaches Beispiel, wie man in PHP ein Cookie setzt und eine Session startet und stoppt:

```php
// Setzen eines Cookies
$_SESSION["username"] = "jannisfeldman"

// Starten einer Session
session_start();
// Sessions müssen immer vor dem man $_SESSION braucht gestartet werden.

// Stoppen einer Session
session_destroy();
```