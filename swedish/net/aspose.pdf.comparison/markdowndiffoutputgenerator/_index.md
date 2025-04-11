---
title: Class MarkdownDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator klass. Representerar en klass för att generera markdown-representation av textskillnader. På grund av markdown-syntaxen är det inte möjligt att visa ändringar av vita tecken. Val av ändringar gör att vita tecken läggs till runt formatering, annars kommer markdown-visaren inte att visa texten korrekt. Rader som har tagits bort indikeras av stycke markering.
type: docs
weight: 3250
url: /sv/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator klass

Representerar en klass för att generera markdown-representation av textskillnader. På grund av markdown-syntaxen är det inte möjligt att visa ändringar av vita tecken. Val av ändringar gör att vita tecken läggs till runt formatering, annars kommer markdown-visaren inte att visa texten korrekt. Rader som har tagits bort indikeras av - stycke markering.

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Genererar utdata baserat på skillnaderna mellan texter och sparar det till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Genererar utdata baserat på skillnaderna mellan texter och sparar det till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Genererar utdata baserat på skillnaderna mellan texter och sparar det till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Genererar utdata baserat på skillnaderna mellan texter och sparar det till en fil. |

### Se Även

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)