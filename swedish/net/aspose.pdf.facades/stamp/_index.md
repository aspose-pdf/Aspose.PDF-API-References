---
title: "Klass Stamp"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.Stamp klass. Klass som representerar en stämpel."
type: docs
weight: 4840
url: /sv/net/aspose.pdf.facades/stamp/
---
## Stamp class

Klass som representerar en stämpel.

```csharp
public sealed class Stamp
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Stamp](stamp/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Hämtar eller anger ett BlendingColorSpace‑värde som definierar ett färgrymd som används för att utföra transparens‑ och blandningsoperationer på sidan. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Hämtar eller anger bakgrundsstatus. Om sant placeras stämpeln som bakgrund på den stämplade sidan. Som standard är den falsk. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Hämtar eller anger opaciteten för stämpeln. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Hämtar eller anger sidnummer. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Hämtar eller anger en array med sidnummer som kommer att påverkas av stämpeln. Om Pages = null påverkas alla dokumentets sidor. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Hämtar eller anger kvaliteten på bildstämpeln i procent. Tillåtna värden 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Hämtar eller anger rotationen för stämpeln i grader. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Hämtar eller anger identifierare för stämpel. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Anger bild som kommer att användas som stämpel. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Anger bild som en stämpel. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Anger text som stämpel. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Anger PDF‑fil och sidnummer som kommer att användas som stämpel. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Anger PDF‑fil och sidnummer som kommer att användas som stämpel. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Anger texttillstånd för stämpeltext. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Anger storlek på bildstämpel. Bilden skalas enligt de angivna värdena. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Anger position på sidan där stämpeln kommer att placeras. |

### Se även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


