---
title: "Klass LoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LoadOptions-klass. LoadOptions-typen innehåller abstraktionsnivå för individuella laddningsalternativ"
type: docs
weight: 6260
url: /sv/net/aspose.pdf/loadoptions/
---
## LoadOptions class

LoadOptions-typen innehåller abstraheringsnivån för enskilda laddningsalternativ.

```csharp
public abstract class LoadOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som `LoadOptions` beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


