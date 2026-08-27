---
title: "Klass SubmitFormAction"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.SubmitFormAction klass. Klass som beskriver submitform‑åtgärd"
type: docs
weight: 2740
url: /sv/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

Klass som beskriver submit-form‑åtgärd.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | Initierar SubmitFormAction‑objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Hämtar eller anger flaggor för submit‑åtgärd |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Nästa åtgärder i sekvensen. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | Destinations‑URL. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Hämtar sträng för ECMAScript‑åtgärd. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Om angivet, ska alla inskickade fältvärden som representerar datum konverteras till standardformatet. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Om angivet, ska F‑posten i den inskickade FDF vara en filspecificering som innehåller ett inbäddat filström som representerar PDF‑filen som FDF‑filen skickas från. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Om angivet, ska den inskickade FDF utesluta F‑posten. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Om angivet, ska den endast inkludera de markup‑annotationer vars T‑post matchar namnet på den aktuella användaren. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Om rensad, specificerar Fields‑arrayen vilka fält som ska inkluderas i inskickningen. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Om angivet, ska fältnamn och -värden skickas i HTML‑formulärformat. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Om angivet, ska fältnamn och -värden skickas med en HTTP‑GET‑begäran. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Om angivet, ska den inskickade FDF‑filen inkludera alla markup‑annotationer i det underliggande PDF‑dokumentet. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Om angivet, ska den inskickade FDF‑filen inkludera innehållet i alla inkrementella uppdateringar. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Om angivet, ska alla fält som anges av Fields‑arrayen och Include/Exclude‑flaggan skickas. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Om angivet, ska koordinaterna för musklicken som orsakade submit‑form‑åtgärden överföras som en del av formulärdata. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Om den är angiven, ska dokumentet skickas som PDF med MIME-innehållstypen application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Om den är angiven ska fältnamn och värden skickas som XFDF. |

### Se även

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


