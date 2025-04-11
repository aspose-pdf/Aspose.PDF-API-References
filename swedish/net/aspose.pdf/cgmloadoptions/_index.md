---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CgmLoadOptions klass. Innehåller alternativ för att ladda/importera CGM-fil till pdf-dokument
type: docs
weight: 3010
url: /sv/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions klass

Innehåller alternativ för att ladda/importera CGM-fil till pdf-dokument.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Skapar standardladdningsalternativ för att konvertera CGM-fil till pdf-dokument. Standard pdf-sidstorlek - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Skapar laddningsalternativ med definierad !:pageSize. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller ställer in flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Hämtar eller ställer in utdata sidstorlek för import. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och laddningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall laddningsoperationen ska upphöra. |

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)