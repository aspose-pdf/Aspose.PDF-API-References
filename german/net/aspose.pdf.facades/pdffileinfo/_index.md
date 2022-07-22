---
title: PdfFileInfo
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert eine Klasse für den Zugriff auf Metainformationen eines PDF-Dokuments.
type: docs
weight: 2530
url: /de/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

Repräsentiert eine Klasse für den Zugriff auf Metainformationen eines PDF-Dokuments.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfFileInfo](pdffileinfo#constructor)() | Initialisiert eine neue Instanz der Klasse Aspose.Pdf.Facades.PdfFileInfo mit Standardwerten. |
| [PdfFileInfo](pdffileinfo#constructor_1)(Document) | Initialisiert neu[`PdfFileInfo`](../pdffileinfo) Objekt auf Basis der*document* . |
| [PdfFileInfo](pdffileinfo#constructor_2)(Stream) | Initialisiert eine neue Instanz der Klasse Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_4)(string) | Initialisiert eine neue Instanz der Klasse Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_3)(Stream, string) | Initialisiert eine neue Instanz der Klasse Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_5)(string, string) | Initialisiert eine neue Instanz der Klasse Aspose.Pdf.Facades.PdfFileInfo. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author) { get; set; } | Ruft die Autoreninformationen des PDF-Dokuments ab oder legt sie fest. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate) { get; set; } | Ruft die CreationDate-Informationen des PDF-Dokuments ab oder legt sie fest. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator) { get; set; } | Ruft die Erstellerinformationen des PDF-Dokuments ab oder legt sie fest. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ruft die Dokumentfassade ab, an der gearbeitet wird. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection) { get; } | Gibt „true“ zurück, wenn die aktuelle Eingabedatei eine „Portfolio“-Datei ist, die eine Sammlung von PDF-Dateien enthält. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword) { get; } | Gibt „true“ zurück, wenn ein Passwort benötigt wird, um Berechtigungen oder Dokumentsicherheitseigenschaften zu ändern. Beachten Sie, dass diese Eigenschaft nur gelesen werden kann, wenn ein gültiges Passwort angegeben wurde[`PdfFileInfo`](../pdffileinfo) constructor. Falls PasswordType Inaccessible ist (bedeutet, dass ein ungültiges Passwort angegeben wurde), schlägt das Lesen dieser Eigenschaft fehl[`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception) . |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword) { get; } | Gibt wahr zurück, wenn ein Passwort benötigt wird, um ein passwortgeschütztes PDF-Dokument zu öffnen. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header) { get; set; } | Ruft die benutzerdefinierten Informationen des PDF-Dokuments ab oder legt sie fest. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted) { get; } | Prüft, ob das PDF-Dokument verschlüsselt ist. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile) { get; } | Prüft, ob die Quelleingabe eine gültige PDF-Datei ist. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords) { get; set; } | Ruft die Schlüsselwortinformationen des PDF-Dokuments ab oder legt sie fest. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate) { get; set; } | Ruft die ModDate-Datumsinformationen des PDF-Dokuments ab oder legt sie fest. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages) { get; } | Ruft die Anzahl der Dokumentseiten ab. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype) { get; } | Gibt den Passworttyp zurück, der zum Erstellen der PdfFileInfo-Instanz übergeben wurde. Siehe mögliche Werte in[`PasswordType`](./passwordtype) . Beachten Sie, dass das PDF-Dokument sowohl mit dem Benutzerpasswort (oder Öffnen) als auch mit dem Besitzerpasswort (oder Berechtigungen, Bearbeiten) geöffnet werden kann. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer) { get; } | Ruft die Herstellerinformationen des PDF-Dokuments ab. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject) { get; set; } | Ruft die Betreffinformationen des PDF-Dokuments ab oder legt sie fest. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title) { get; set; } | Ruft die Titelinformationen des PDF-Dokuments ab oder legt sie fest. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation) { get; set; } | Verwendet strenge Validierungsregeln über using[`IsPdfFile`](./ispdffile) Eigentum. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf#bindpdf)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialisiert die Fassade. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo)() | Löscht alle Metainformationen des PDF-Dokuments. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close)() | Deinitialisiert die Instanz. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Entsorgt die Fassade. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege)() | Ruft die Privilegeinstellungen für PDF-Dokumente ab. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo)(string) | Ruft angepasste Informationen des PDF-Dokuments mit dem Eigenschaftsnamen ab. Wenn keine Eigenschaft mit dem Namen übereinstimmt, wird eine leere Zeichenfolge zurückgegeben. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight)(int) | Ruft die Höhe der angegebenen Seite ab. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation)(int) | Ruft die Drehung der angegebenen Seite ab. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth)(int) | Ruft die Breite der angegebenen Seite ab. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset)(int) | Ruft den horizontalen Versatz des angegebenen Seitenanzeigebereichs ab. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset)(int) | Ruft den vertikalen Versatz des angegebenen Seitenanzeigebereichs ab. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion)() | Ruft die Versionsinformationen des PDF-Dokuments ab. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save)(Stream) | Speichert das PDF-Dokument in der angegebenen Datei. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save_1)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo#savenewinfo_1)(string) | Aktualisiertes PDF-Dokument in angegebener Datei speichern. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp)(string) | Ändert die explizit angegebenen Eigenschaften durch Setzen von Dateiinformationen, andere Eigenschaften bleiben erhalten. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo)(string, string) | Legt benutzerdefinierte Informationen des PDF-Dokuments fest. |

### Siehe auch

* class [SaveableFacade](../saveablefacade)
* namensraum [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
