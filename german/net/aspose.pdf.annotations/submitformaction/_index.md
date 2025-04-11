---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.SubmitFormAction-Klasse. Klasse, die die SubmitForm-Aktion beschreibt
type: docs
weight: 2640
url: /de/net/aspose.pdf.annotations/submitformaction/
---
## Klasse SubmitFormAction

Klasse, die die Submit-Form-Aktion beschreibt.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | Initialisiert das SubmitFormAction-Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Ruft die Flags der Submit-Aktion ab oder legt sie fest. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Nächste Aktionen in der Reihenfolge. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | Ziel-URL. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Ruft den String für die ECMAScript-Aktion ab. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Wenn gesetzt, werden alle übermittelten Feldwerte, die Daten darstellen, in das Standardformat konvertiert. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Wenn gesetzt, soll der F-Eintrag des übermittelten FDF eine Dateispezifikation enthalten, die einen eingebetteten Dateistream darstellt, der die PDF-Datei enthält, von der das FDF übermittelt wird. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Wenn gesetzt, soll das übermittelte FDF den F-Eintrag ausschließen. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Wenn gesetzt, soll es nur die Markup-Anmerkungen einschließen, deren T-Eintrag mit dem Namen des aktuellen Benutzers übereinstimmt. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Wenn gelöscht, gibt das Fields-Array an, welche Felder in die Übermittlung einbezogen werden sollen. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Wenn gesetzt, sollen die Feldnamen und -werte im HTML-Formularformat übermittelt werden. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Wenn gesetzt, sollen die Feldnamen und -werte mit einer HTTP-GET-Anforderung übermittelt werden. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Wenn gesetzt, soll die übermittelte FDF-Datei alle Markup-Anmerkungen im zugrunde liegenden PDF-Dokument enthalten. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Wenn gesetzt, soll die übermittelte FDF-Datei die Inhalte aller inkrementellen Updates enthalten. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Wenn gesetzt, sollen alle Felder, die durch das Fields-Array und das Include/Exclude-Flag bezeichnet sind, übermittelt werden. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Wenn gesetzt, sollen die Koordinaten des Mausklicks, der die Submit-Form-Aktion ausgelöst hat, als Teil der Formulardaten übermittelt werden. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Wenn gesetzt, soll das Dokument als PDF übermittelt werden, unter Verwendung des MIME-Inhaltstyps application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Wenn gesetzt, sollen die Feldnamen und -werte als XFDF übermittelt werden. |

### Siehe auch

* Klasse [PdfAction](../pdfaction/)
* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)