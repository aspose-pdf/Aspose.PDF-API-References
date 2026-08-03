---
title: "Klass SvgLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.SvgLoadOptions-klass. Representerar alternativ för inläsning/import av SVG-fil till pdf-dokument"
type: docs
weight: 10390
url: /sv/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

Representerar alternativ för att läsa in/importera SVG-fil i pdf-dokument.

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
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Justera pdf-sidans storlek till svg-storlek |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Hämtar eller anger sidinformation som ska tillämpas under inläsning av dokumentet. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Tillåter val av konverteringsmotor som ska användas under konverteringen. För närvarande är den nya motorn i B-testningsstadiet, så detta värde är som standard satt till ConversionEngines.LegacyEngine |

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


