---
title: "PdfFileSecurity"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt das Verschlüsseln oder Entschlüsseln einer PDF-Datei mit Besitzer- oder Benutzerpasswort dar, wobei die Sicherheitseinstellungen und das Passwort geändert werden."
type: docs
weight: 300
url: /de/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

Stellt das Verschlüsseln oder Entschlüsseln einer PDF-Datei mit Besitzer- oder Benutzerpasswort dar, wobei die Sicherheitseinstellungen und das Passwort geändert werden.

Der Typ PdfFileSecurity stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | Initialisiert eine neue Instanz der Klasse PdfFileSecurity |
| PdfFileSecurity(input_file, output_file) | Initialisiert eine neue Instanz der Klasse PdfFileSecurity |
| PdfFileSecurity() | Initialisiert das Objekt von PdfFileSecurity. |
| PdfFileSecurity(document) | Initialisiert eine neue Instanz der Klasse PdfFileSecurity |
| PdfFileSecurity(document, output_file) | Initialisiert eine neue Instanz der Klasse PdfFileSecurity |
| PdfFileSecurity(document, output_stream) | Initialisiert eine neue Instanz der Klasse PdfFileSecurity |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| allow_exceptions | Wenn dieser Wert auf true gesetzt ist, wird bei einem Vorgangsfehler eine Ausnahme ausgelöst. Andernfalls gibt die Methode bei einem Fehler false zurück und die letzte Ausnahme kann über die Eigenschaft LastException abgefragt werden. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_file) | Initialisiert die Fassade. |
| bind_pdf(src_stream) | Initialisiert die Fassade. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save(dest_file) | Speichert das PDF-Dokument in die angegebene Datei. |
| save(dest_stream) | Speichert das PDF-Dokument in den angegebenen Stream. |
| encrypt_file(user_password, owner_password, privilege, key_size) | Verschlüsselt die PDF-Datei mit Benutzerpasswort und Besitzerpasswort und legt die Zugriffsrechte des Dokuments fest.<br/>            Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird <br/>            durch eine zufällige Zeichenfolge ersetzt, wenn das übergebene Besitzerpasswort null oder leer ist.<br/>            Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | Verschlüsselt die PDF-Datei mit Benutzerpasswort und Besitzerpasswort und legt die Zugriffsrechte des Dokuments fest.<br/>            Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird <br/>            durch eine zufällige Zeichenfolge ersetzt, wenn das übergebene Besitzerpasswort null oder leer ist.<br/>            Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. <br/>            Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende <br/>            Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt.<br/>            Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. |
| set_privilege(privilege) | Setzt die PDF-Datei-Sicherheit mit leeren Benutzer-/Besitzerpasswörtern.<br/>            Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ergänzt.<br/>            Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. |
| set_privilege(user_password, owner_password, privilege) | Setzt die PDF-Datei-Sicherheit mit dem ursprünglichen Passwort.<br/>            Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. |
| change_password(owner_password, new_user_password, new_owner_password) | Ändert das Benutzerpasswort und das Besitzerpasswort mittels Besitzerpasswort und behält die ursprünglichen Sicherheitseinstellungen bei.<br/>             Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird <br/>             durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist.<br/>             Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Ändert das Benutzerpasswort und das Passwort mittels Besitzerpasswort und ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit.<br/>            Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird <br/>            durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist.<br/>            Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Ändert das Benutzerpasswort und das Passwort mittels Besitzerpasswort und ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit.<br/>            Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird <br/>            durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist.<br/>            Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. <br/>            Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende <br/>            Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt.<br/>            Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. |
| try_change_password(owner_password, new_user_password, new_owner_password) | Ändert das Benutzerpasswort und das Besitzerpasswort mittels Besitzerpasswort und behält die ursprünglichen Sicherheitseinstellungen bei.<br/>             Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird <br/>             Wirft keine Ausnahme, wenn der Vorgang fehlgeschlagen ist.<br/>             mit einer zufälligen Zeichenfolge, wenn das neue Besitzerpasswort null oder leer ist. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Ändert das Benutzerpasswort und das Passwort mittels Besitzerpasswort und ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit.<br/>            Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird <br/>            mit einer zufälligen Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist.<br/>            Wirft keine Ausnahme, wenn der Vorgang fehlgeschlagen ist. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit.<br/>            Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird <br/>            durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist.<br/>            Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. <br/>            Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende <br/>            Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt.<br/>            Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. |
| close() | Schließt die Fassade. |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und legt die Zugriffsrechte des Dokuments fest.<br/>            Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird <br/>            durch eine zufällige Zeichenfolge ersetzt, wenn das übergebene Besitzerpasswort null oder leer ist.<br/>            Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. |
| decrypt_file(owner_password) | Entschlüsselt ein verschlüsseltes Pdf-Dokument mit dem Besitzerpasswort. <br/>            Wenn das Dokument kein Besitzerpasswort hat, ist die Verwendung des Benutzerpassworts erlaubt.<br/>            Wirft eine Ausnahme, wenn der Vorgang fehlschlägt. |
| try_decrypt_file(owner_password) | Entschlüsselt ein verschlüsseltes Pdf-Dokument mit dem Besitzerpasswort. <br/>            Wenn das Dokument kein Besitzerpasswort hat, ist die Verwendung des Benutzerpassworts erlaubt.<br/>            Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. |
| try_set_privilege(user_password, owner_password, privilege) | Setzt die Sicherheit der Pdf-Datei mit dem ursprünglichen Passwort.<br/>            Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

