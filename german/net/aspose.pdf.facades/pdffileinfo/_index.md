---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileInfo-Klasse. Stellt eine Klasse zum Zugriff auf Metainformationen von PDF-Dokumenten dar
type: docs
weight: 4520
url: /de/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo-Klasse

Stellt eine Klasse zum Zugriff auf Metainformationen von PDF-Dokumenten dar.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Initialisiert eine neue Instanz der Aspose.Pdf.Facades.PdfFileInfo-Klasse mit Standardwerten. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Initialisiert ein neues `PdfFileInfo`-Objekt basierend auf dem *Dokument*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Initialisiert eine neue Instanz der Aspose.Pdf.Facades.PdfFileInfo-Klasse. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Initialisiert eine neue Instanz der Aspose.Pdf.Facades.PdfFileInfo-Klasse. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Initialisiert eine neue Instanz der Aspose.Pdf.Facades.PdfFileInfo-Klasse. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Initialisiert eine neue Instanz der Aspose.Pdf.Facades.PdfFileInfo-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Ruft die Autoreninformationen des PDF-Dokuments ab oder legt sie fest. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Ruft die Erstellungsdatum-Informationen des PDF-Dokuments ab oder legt sie fest. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Ruft die Erstellerinformationen des PDF-Dokuments ab oder legt sie fest. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ruft das Dokument ab, an dem die Fassade arbeitet. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Gibt true zurück, wenn die aktuelle Eingabedatei eine 'Portfolio'-Datei ist, die eine Sammlung von PDF-Dateien enthält. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Gibt true zurück, wenn ein Passwort benötigt wird, um Berechtigungen oder die Sicherheitseigenschaft des Dokuments zu ändern. Beachten Sie, dass diese Eigenschaft nur gelesen werden kann, wenn ein gültiges Passwort im `PdfFileInfo`-Konstruktor angegeben wurde. Wenn der PasswordType unzugänglich ist (was bedeutet, dass ein ungültiges Passwort angegeben wurde), schlägt das Lesen dieser Eigenschaft mit [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/) fehl. |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Gibt true zurück, wenn ein Passwort benötigt wird, um ein passwortgeschütztes PDF-Dokument zu öffnen. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Ruft die benutzerdefinierten Informationen des PDF-Dokuments ab oder legt sie fest. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Überprüft, ob das PDF-Dokument verschlüsselt ist. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Überprüft, ob die Quelldatei eine gültige PDF-Datei ist. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Ruft die Schlüsselwortinformationen des PDF-Dokuments ab oder legt sie fest. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Ruft die ModDate-Dateninformationen des PDF-Dokuments ab oder legt sie fest. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Ruft die Anzahl der Seiten im Dokument ab. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Gibt den Typ des Passworts zurück, das zur Erstellung der PdfFileInfo-Instanz übergeben wurde. Siehe mögliche Werte in [`PasswordType`](./passwordtype/). Beachten Sie, dass das PDF-Dokument sowohl mit dem Benutzer- (oder Öffnungs-) Passwort als auch mit dem Eigentümer- (oder Berechtigungs-, Bearbeitungs-) Passwort geöffnet werden kann. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Ruft die Produzenteninformationen des PDF-Dokuments ab. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Ruft die Betreffinformationen des PDF-Dokuments ab oder legt sie fest. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Ruft die Titelinformationen des PDF-Dokuments ab oder legt sie fest. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Verwendet strenge Validierungsregeln über die Verwendung der [`IsPdfFile`](./ispdffile/) Eigenschaft. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialisiert die Fassade. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Löscht alle Metainformationen des PDF-Dokuments. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Deinitialisiert die Instanz. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Ruft die Berechtigungseinstellungen des PDF-Dokuments ab. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Ruft benutzerdefinierte Informationen des PDF-Dokuments mit dem Eigenschaftsnamen ab. Wenn es keine Übereinstimmung mit dem Namen gibt, wird eine leere Zeichenfolge zurückgegeben. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Ruft die Höhe der angegebenen Seite ab. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Ruft die Drehung der angegebenen Seite ab. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Ruft die Breite der angegebenen Seite ab. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Ruft den horizontalen Versatz des angezeigten Bereichs der angegebenen Seite ab. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Ruft den vertikalen Versatz des angezeigten Bereichs der angegebenen Seite ab. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Ruft die Versionsinformationen des PDF-Dokuments ab. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Speichert das PDF-Dokument in der angegebenen Datei. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Speichert das aktualisierte PDF-Dokument in der angegebenen Datei. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Ändert die Eigenschaften, die ausdrücklich durch Festlegen der Dateiinformationen angegeben sind, andere Eigenschaften bleiben unverändert. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Setzt benutzerdefinierte Informationen des PDF-Dokuments. |

### Siehe auch

* Klasse [SaveableFacade](../saveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)