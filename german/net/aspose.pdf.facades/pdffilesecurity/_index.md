---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSecurity-Klasse. Stellt das Verschlüsseln oder Entschlüsseln einer Pdf-Datei mit Eigentümer- oder Benutzerpasswort dar, ändert die Sicherheitseinstellungen und das Passwort
type: docs
weight: 4550
url: /de/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity-Klasse

Stellt das Verschlüsseln oder Entschlüsseln einer Pdf-Datei mit Eigentümer- oder Benutzerpasswort dar, ändert die Sicherheitseinstellungen und das Passwort.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Initialisiert das Objekt von PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Initialisiert ein neues `PdfFileSecurity`-Objekt auf Basis des *Dokuments*. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt das Dokument zurück, an dem die Fassade arbeitet. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Gibt die Ausnahme zurück, die durch die letzte Operation ausgelöst wurde. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Initialisiert die Fassade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Initialisiert die Fassade. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Ändert das Benutzerpasswort und das Eigentümerpasswort durch das Eigentümerpasswort, behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerpasswort und das neue Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Wirft eine Ausnahme, wenn der Prozess fehlschlägt. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändert das Benutzerpasswort und das Passwort durch das Eigentümerpasswort, ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Wirft eine Ausnahme, wenn der Prozess fehlschlägt. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändert das Benutzerpasswort und das Passwort durch das Eigentümerpasswort, ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) sind jedoch ungültig und die entsprechende Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt. Wirft eine Ausnahme, wenn der Prozess fehlschlägt. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Schließt die Fassade. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Entschlüsselt ein verschlüsseltes Pdf-Dokument durch das Eigentümerpasswort. Wenn das Dokument kein Eigentümerpasswort hat, ist es erlaubt, das Benutzerpasswort zu verwenden. Wirft eine Ausnahme, wenn der Prozess fehlschlägt. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Eigentümerpasswort und setzt die Zugriffsrechte des Dokuments. Das Benutzerpasswort und das Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Eigentümerpasswort null oder leer ist. Wirft eine Ausnahme, wenn der Prozess fehlschlägt. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Eigentümerpasswort und setzt die Zugriffsrechte des Dokuments. Das Benutzerpasswort und das Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Eigentümerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) sind jedoch ungültig und die entsprechende Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt. Wirft eine Ausnahme, wenn der Prozess fehlschlägt. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Setzt die Pdf-Dateisicherheit mit leeren Benutzer-/Eigentümerpasswörtern. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge hinzugefügt. Wirft eine Ausnahme, wenn der Prozess fehlschlägt. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Setzt die Pdf-Dateisicherheit mit dem ursprünglichen Passwort. Wirft eine Ausnahme, wenn der Prozess fehlschlägt. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Ändert das Benutzerpasswort und das Eigentümerpasswort durch das Eigentümerpasswort, behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerpasswort und das neue Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Prozess fehlschlägt. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändert das Benutzerpasswort und das Passwort durch das Eigentümerpasswort, ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Prozess fehlschlägt. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändert das Benutzerpasswort und das Passwort durch das Eigentümerpasswort, ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) sind jedoch ungültig und die entsprechende Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt. Wirft keine Ausnahme, wenn der Prozess fehlschlägt. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Entschlüsselt ein verschlüsseltes Pdf-Dokument durch das Eigentümerpasswort. Wenn das Dokument kein Eigentümerpasswort hat, ist es erlaubt, das Benutzerpasswort zu verwenden. Wirft keine Ausnahme, wenn der Prozess fehlschlägt. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Eigentümerpasswort und setzt die Zugriffsrechte des Dokuments. Das Benutzerpasswort und das Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Eigentümerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Prozess fehlschlägt. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Setzt die Pdf-Dateisicherheit mit dem ursprünglichen Passwort. Wirft keine Ausnahme, wenn der Prozess fehlschlägt. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)