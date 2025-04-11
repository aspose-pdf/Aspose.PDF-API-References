---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: خاصية الطابع. تحصل أو تعين دوران الطابع بالدرجات
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/stamp/rotation/
---
## خاصية Stamp.Rotation

تحصل أو تعين دوران الطابع بالدرجات.

```csharp
public float Rotation { get; set; }
```

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)