---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Stamp-egenskap. Hämtar eller ställer in en array med sidnummer som kommer att påverkas av stämpeln. Om Pages = null påverkas alla sidor i dokumentet
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages-egenskap

Hämtar eller ställer in en array med sidnummer som kommer att påverkas av stämpeln. Om Pages = null påverkas alla sidor i dokumentet.

```csharp
public int[] Pages { get; set; }
```

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se Även

* klass [Stamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)