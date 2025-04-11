---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgLoadOptions klass. Representerar alternativ för att ladda/importera SVG-fil till pdf-dokument
type: docs
weight: 10210
url: /sv/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions klass

Representerar alternativ för att ladda/importera SVG-fil till pdf-dokument.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Justera pdf-sidstorlek till svg-storlek |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller ställer in flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Hämtar eller ställer in sidinformation som ska tillämpas under inläsning av dokumentet. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och inläsningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall inläsningsoperationen ska upphöra. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Tillåter att välja konverteringsmotor som kommer att användas under konverteringen. För närvarande är den nya motorn i B-teststadiet, så detta värde är som standard inställt på ConversionEngines.LegacyEngine |

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)