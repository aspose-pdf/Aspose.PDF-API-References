---
title: SectionsSearchDepth
second_title: Aspose.PDF för .NET API Referens
description: Hämtar eller ställer in värde som anger hur många gånger sekventiella sökningar efter mer fina strukturelement kommer att utföras. Standardsökdjupet är 3. Det betyder tre sökningar efter horisontellt delade avsnitt rubriker stycken etc och tre sökningar efter vertikalt delade ettor kolumner.
type: docs
weight: 40
url: /sv/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

Hämtar eller ställer in värde som anger hur många gånger sekventiella sökningar efter mer fina strukturelement kommer att utföras. Standardsökdjupet är 3. Det betyder tre sökningar efter horisontellt delade avsnitt (rubriker, stycken etc) och tre sökningar efter vertikalt delade ettor (kolumner).

```csharp
public int SectionsSearchDepth { get; set; }
```

### Anmärkningar

Ökning av detta värde kan leda till mindre sämre prestanda utan synliga förändringar i sökresultatet. En minskning av detta värde kan leda till felaktig bestämning av stycken i sektioner. Vi rekommenderar inte att du ställer in ett värde som är lägre än standard om du inte är det önskan att bara få "grova" delar av sidstrukturen.

### Se även

* class [ParagraphAbsorber](../../paragraphabsorber)
* namnutrymme [Aspose.Pdf.Text](../../paragraphabsorber)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
