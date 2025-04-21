---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: ParagraphAbsorber-egenskap. Hämtar eller ställer in värde som instruerar hur många gånger sekventiella sökningar efter mer fina element av struktur kommer att utföras. Standard sökdjup är 3. Det betyder tre sökningar efter horisontellt delade sektioner och tre sökningar efter vertikalt delade.
type: docs
weight: 50
url: /sv/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth-egenskap

Hämtar eller ställer in värde som instruerar hur många gånger sekventiella sökningar efter mer fina element av struktur kommer att utföras. Standard sökdjup är 3. Det betyder tre sökningar efter horisontellt delade sektioner (rubriker, stycken etc.) och tre sökningar efter vertikalt delade (kolumner).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Kommentarer

Ökning av detta värde kan leda till en mindre minskning av prestanda utan synliga förändringar i sökresultatet. Minskning av detta värde kan leda till felaktig bestämning av stycken i sektioner. Vi rekommenderar inte att ställa in värdet lägre än standard om du inte önskar få endast 'grova' element av sidstruktur.

### Se Även

* klass [ParagraphAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../../)