---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsLoadOptions klass. Representerar alternativ för att ladda/importera .mht-fil till pdf-dokument
type: docs
weight: 9730
url: /sv/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions klass

Representerar alternativ för att ladda/importera .mht-fil till pdf-dokument.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller sätter flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Hämtar eller sätter sökvägar för typsnittsmappar. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformatet som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och inläsningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall inläsningsoperationen ska upphöra. |

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)