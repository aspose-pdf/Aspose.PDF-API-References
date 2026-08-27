---
title: "ParagraphAbsorber.SectionsSearchDepth"
second_title: "Aspose.PDF för .NET API‑referens"
description: "ParagraphAbsorber egenskap. Hämtar eller anger värde som instruerar hur många gånger sekventiella sökningar efter finare element i strukturen ska utföras. Standard sökdjup är 3. Det betyder tre sökningar för horisontellt delade avsnitt, rubriker, stycken osv och tre sökningar för vertikalt delade kolumner"
type: docs
weight: 50
url: /sv/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

Hämtar eller anger värdet som bestämmer hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken osv) och tre sökningar för vertikalt delade (kolumner).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Anmärkningar

Att öka detta värde kan leda till en liten minskning av prestanda utan synliga förändringar i sökresultatet. Att minska detta värde kan leda till felaktig bestämning av stycken i avsnitt. Vi rekommenderar inte att sätta värdet lägre än standard om du inte önskar få endast 'rough' element i sidstrukturen.

### Se även

* class [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


