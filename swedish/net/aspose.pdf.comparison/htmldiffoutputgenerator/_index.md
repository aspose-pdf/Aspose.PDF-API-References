---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.HtmlDiffOutputGenerator klass. Representerar en klass för att generera html-representation av textskillnader. Rader som har tagits bort indikeras av styckemärke
type: docs
weight: 3200
url: /sv/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator klass

Representerar en klass för att generera html-representation av textskillnader. Rader som har tagits bort indikeras av styckemärke.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Skapar en instans av `HtmlDiffOutputGenerator` klass. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Skapar en instans av `HtmlDiffOutputGenerator` klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Hämtar och sätter CSS-stilsträngen för Delete-operationen. Exempel: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Hämtar och sätter CSS-stilsträngen för Equal-operationen. Exempel: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Hämtar och sätter CSS-stilsträngen för Insert-operationen. Exempel: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Hämtar eller sätter textdekoration: linje-genom stil för delete-operationen. Standardvärde är `False`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Genererar utdata baserat på skillnaderna mellan texterna och sparar det till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Genererar utdata baserat på skillnaderna mellan texterna och sparar det till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Genererar utdata baserat på skillnaderna mellan texterna och sparar det till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Genererar utdata baserat på skillnaderna mellan texterna och sparar det till en fil. |

### Se Även

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)