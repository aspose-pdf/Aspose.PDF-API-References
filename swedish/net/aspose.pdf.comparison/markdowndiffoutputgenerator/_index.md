---
title: "Klass MarkdownDiffOutputGenerator"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator-klass. Representerar en klass för att generera markdown‑representation av textskillnader. På grund av markdown‑syntaxen är det inte möjligt att visa förändringar av blankstegstecken. Val av förändringar gör att blankstegstecken läggs till runt formatering, annars kommer markdown‑visaren inte att visa texten korrekt. Borttagna radbrytningar indikeras med ett styckesmärke."
type: docs
weight: 3360
url: /sv/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class

Representerar en klass för att generera markdown‑representation av textskillnader. På grund av markdown‑syntaxen är det inte möjligt att visa ändringar av blankstegstecken. Val av ändringar innebär att lägga till blankstegstecken runt formatering, annars kommer markdown‑visaren inte att visa texten korrekt. Borttagna radbrytningar indikeras med - paragraftecken.

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
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil. |

### Se även

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


