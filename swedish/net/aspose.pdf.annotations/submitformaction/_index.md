---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.SubmitFormAction klass. Klass som beskriver submitform åtgärd
type: docs
weight: 2640
url: /sv/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction klass

Klass som beskriver submit-form åtgärd.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | Initierar SubmitFormAction objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Hämtar eller ställer in flaggor för submit åtgärd |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Nästa åtgärder i sekvens. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | Mål-URL. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Hämtar sträng för ECMAScript Åtgärd. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Om inställd, ska alla inlämnade fältvärden som representerar datum konverteras till standardformatet. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Om inställd, ska F-posten i den inlämnade FDF vara en filspecifikation som innehåller en inbäddad filström som representerar PDF-filen från vilken FDF skickas. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Om inställd, ska den inlämnade FDF utesluta F-posten. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Om inställd, ska den endast inkludera de markup-anteckningar vars T-post matchar namnet på den aktuella användaren. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Om rensad, specificerar Fields-arrayen vilka fält som ska inkluderas i inlämningen. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Om inställd, ska fältnamn och värden skickas i HTML Form-format. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Om inställd, ska fältnamn och värden skickas med en HTTP GET-förfrågan. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Om inställd, ska den inlämnade FDF-filen inkludera alla markup-anteckningar i det underliggande PDF-dokumentet. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Om inställd, ska den inlämnade FDF-filen inkludera innehållet i alla inkrementella uppdateringar. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Om inställd, ska alla fält som anges av Fields-arrayen och Include/Exclude-flaggan skickas. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Om inställd, ska koordinaterna för musknappen som orsakade submit-form åtgärden överföras som en del av formulärdata. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Om inställd, ska dokumentet skickas som PDF, med MIME-innehållstypen application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Om inställd, ska fältnamn och värden skickas som XFDF. |

### Se Även

* klass [PdfAction](../pdfaction/)
* namnrymd [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* sammansättning [Aspose.PDF](../../)