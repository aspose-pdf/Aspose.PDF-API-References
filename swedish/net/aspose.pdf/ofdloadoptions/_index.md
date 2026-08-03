---
title: "Klass OfdLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.OfdLoadOptions klass. Laddningsalternativ för OFD-format."
type: docs
weight: 7200
url: /sv/net/aspose.pdf/ofdloadoptions/
---
## OfdLoadOptions class

Laddningsalternativ för OFD-format.

```csharp
public class OfdLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OfdLoadOptions](ofdloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


