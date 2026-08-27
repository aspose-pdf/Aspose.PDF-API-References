---
title: "Klass HtmlDiffOutputGenerator"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Comparison.HtmlDiffOutputGenerator klass. Representerar en klass för att generera html-representation av textskillnader. Borttagna radbrytningar indikeras med ett stycketecken."
type: docs
weight: 3310
url: /sv/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

Representerar en klass för att generera HTML‑representation av textskillnader. Borttagna radbrytningar indikeras med ett stycketecken.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Skapar en instans av `HtmlDiffOutputGenerator`-klassen. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Skapar en instans av `HtmlDiffOutputGenerator`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Hämtar och anger CSS-stilsträngen för Delete‑operationen. Exempel: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Hämtar och anger CSS-stilsträngen för Equal‑operationen. Exempel: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Hämtar och anger CSS-stilsträngen för Insert‑operationen. Exempel: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Hämta eller ange text-decoration: line-through‑stil för delete‑operationen. Standardvärdet är `False`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |

### Se även

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


