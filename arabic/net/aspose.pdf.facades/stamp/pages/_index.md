---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: خاصية الطابع. تحصل أو تعين مصفوفة بأرقام الصفحات التي ستتأثر بالطابع. إذا كانت الصفحات null، فإن جميع صفحات المستند تتأثر
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/stamp/pages/
---
## خاصية Stamp.Pages

تحصل أو تعين مصفوفة بأرقام الصفحات التي ستتأثر بالطابع. إذا كانت الصفحات = null، فإن جميع صفحات المستند تتأثر.

```csharp
public int[] Pages { get; set; }
```

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)