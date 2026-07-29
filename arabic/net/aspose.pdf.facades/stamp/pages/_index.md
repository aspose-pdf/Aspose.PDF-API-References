---
title: "Stamp.Pages"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Stamp. يحصل أو يحدد مصفوفة بأرقام الصفحات التي سيتأثر بها الختم. إذا كانت Pages null فإن جميع صفحات المستند تتأثر"
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

يحصل أو يعيّن مصفوفة بأرقام الصفحات التي سيتأثر بها الطابع. إذا كان Pages = null فإن جميع صفحات المستند ستتأثر.

```csharp
public int[] Pages { get; set; }
```

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//ضع الختم فقط على الصفحة الأولى والرابعة والسادسة.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


