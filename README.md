# Private Übersichtsseite

Passwortgeschützte, verschlüsselte Einzelseite. Der Inhalt wird ausschließlich
im Browser entschlüsselt (PBKDF2-SHA256 mit 600.000 Runden, AES-256-GCM); im
Repository liegt nur der Chiffretext.

Die Seite wird automatisch erzeugt und überschrieben. Änderungen von Hand an
`index.html` gehen beim nächsten Lauf verloren.
