---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Stamp-egenskap. Hämtar eller ställer in rotationen av stämpeln i grader
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation-egenskap

Hämtar eller ställer in rotationen av stämpeln i grader.

```csharp
public float Rotation { get; set; }
```

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Se Även

* klass [Stamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)