---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Stamp klass. Klass som representerar stämpel
type: docs
weight: 4720
url: /sv/net/aspose.pdf.facades/stamp/
---
## Stämpel klass

Klass som representerar stämpel.

```csharp
public sealed class Stamp
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Stamp](stamp/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Hämtar eller ställer in ett BlendingColorSpace-värde som definierar ett färgrum som används för att utföra transparens- och blandningsoperationer på sidan. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Hämtar eller ställer in bakgrundsstatus. Om sant kommer stämpeln att placeras som bakgrund på den stämplade sidan. Som standard är det inställt på falskt. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Hämtar eller ställer in opaciteten för stämpeln. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Hämtar eller ställer in sidnumret. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Hämtar eller ställer in en array med sidnummer som kommer att påverkas av stämpeln. Om Pages = null påverkas alla sidor i dokumentet. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Hämtar eller ställer in kvaliteten på bildstämpeln i procent. Giltiga värden 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Hämtar eller ställer in rotationen av stämpeln i grader. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Hämtar eller ställer in identifieraren för stämpeln. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Ställer in bilden som kommer att användas som stämpel. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Ställer in bilden som en stämpel. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Ställer in text som stämpel. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Ställer in PDF-fil och sidnummer som kommer att användas som stämpel. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Ställer in PDF-fil och sidnummer som kommer att användas som stämpel. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Ställer in textstatus för stämpeltexten. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Ställer in storleken på bildstämpeln. Bilden kommer att skalas enligt de angivna värdena. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Ställer in positionen på sidan där stämpeln kommer att placeras. |

### Se Även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)