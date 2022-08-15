---
title: PdfFileSecurity
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt das Verschlüsseln oder Entschlüsseln einer PDF-Datei mit Besitzer- oder Benutzerkennwort dar das Ändern der Sicherheitseinstellung und des Kennworts.
type: docs
weight: 2560
url: /de/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Stellt das Verschlüsseln oder Entschlüsseln einer PDF-Datei mit Besitzer- oder Benutzerkennwort dar, das Ändern der Sicherheitseinstellung und des Kennworts.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity#constructor)() | Initialisiert das Objekt von PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity#constructor_1)(Document) | Initialisiert neu[`PdfFileSecurity`](../pdffilesecurity) Objekt auf Basis der*document* . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception) { get; } | Gibt eine Ausnahme zurück, die von der letzten Operation ausgelöst wurde. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_1)(Stream) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_2)(string) | Initialisiert die Fassade. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword)(string, string, string) | Ändert das Benutzerkennwort und das Eigentümerkennwort durch das Eigentümerkennwort, behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerkennwort und das neue Eigentümerkennwort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Löst eine Ausnahme aus, wenn der Prozess fehlgeschlagen ist. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der PDF-Dokumentsicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Löst eine Ausnahme aus, wenn der Prozess fehlgeschlagen ist. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der PDF-Dokumentsicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von Schlüsselgröße und Algorithmuswerten. (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) sind jedoch ungültig und die entsprechende -Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination trifft. Löst eine Ausnahme aus, wenn der Prozess fehlgeschlagen ist. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close)() | Schließt die Fassade. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile)(string) | Entschlüsselt ein verschlüsseltes PDF-Dokument nach Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat, darf es das Benutzerpasswort verwenden. Löst eine Ausnahme aus, wenn der Prozess fehlgeschlagen ist. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile)(string, string, DocumentPrivilege, KeySize) | Verschlüsselt die PDF-Datei mit Benutzerkennwort und Eigentümerkennwort und legt die Zugriffsrechte für das Dokument fest. Das Benutzerkennwort und das Eigentümerkennwort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Eigentümerpasswort null oder leer ist. Löst eine Ausnahme aus, wenn der Prozess fehlgeschlagen ist. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Verschlüsselt die PDF-Datei mit Benutzerpasswort und Eigentümerpasswort und legt die Zugriffsrechte für das Dokument fest. Das Benutzerpasswort und das Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Eigentümerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) sind jedoch ungültig und die entsprechende -Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt. Löst eine Ausnahme aus, wenn der Prozess fehlgeschlagen ist. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege)(DocumentPrivilege) | Legt die PDF-Dateisicherheit mit leeren Benutzer-/Eigentümerkennwörtern fest. Das Eigentümerkennwort wird durch eine zufällige Zeichenfolge hinzugefügt. Löst eine Ausnahme aus, wenn der Vorgang fehlschlägt. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege_1)(string, string, DocumentPrivilege) | Legt die PDF-Dateisicherheit mit dem ursprünglichen Passwort fest. Löst eine Ausnahme aus, wenn der Vorgang fehlschlägt. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword)(string, string, string) | Ändert das Benutzerkennwort und das Eigentümerkennwort durch das Eigentümerkennwort, behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerkennwort und das neue Eigentümerkennwort können null oder leer sein. Das Eigentümerpasswort wird ersetzt Löst keine Ausnahme aus, wenn der Vorgang fehlschlägt. durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der PDF-Dokumentsicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Löst keine Ausnahme aus, wenn der Vorgang fehlschlägt. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der PDF-Dokumentsicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende -Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination trifft. Löst keine Ausnahme aus, wenn der Prozess fehlschlägt. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile)(string) | Entschlüsselt ein verschlüsseltes PDF-Dokument nach Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat, darf es das Benutzerpasswort verwenden. Löst keine Ausnahme aus, wenn der Vorgang fehlschlägt. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile)(string, string, DocumentPrivilege, KeySize) | Verschlüsselt die PDF-Datei mit Benutzerkennwort und Eigentümerkennwort und legt die Zugriffsrechte für das Dokument fest. Das Benutzerkennwort und das Eigentümerkennwort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Eigentümerpasswort null oder leer ist. Löst keine Ausnahme aus, wenn der Vorgang fehlschlägt. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege)(string, string, DocumentPrivilege) | Legt die PDF-Dateisicherheit mit dem ursprünglichen Passwort fest. Löst keine Ausnahme aus, wenn der Prozess fehlschlägt. |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
