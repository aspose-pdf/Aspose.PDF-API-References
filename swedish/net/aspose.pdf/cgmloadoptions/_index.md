---
title: "Klass CgmLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.CgmLoadOptions klass. Innehåller alternativ för att ladda/importera CGM-fil till pdf dokument."
type: docs
weight: 3120
url: /sv/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions class

Innehåller alternativ för att läsa in/importera CGM-fil till ett pdf-dokument.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Skapar standardladdningsalternativ för att konvertera CGM-fil till pdf dokument. Standard pdf sidstorlek - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Skapar laddningsalternativ med definierad !:pageSize. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Hämtar eller anger utdata‑sidstorlek för import. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


