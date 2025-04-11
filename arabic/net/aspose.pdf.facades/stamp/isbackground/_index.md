---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: خاصية Stamp. تحصل أو تعين حالة الخلفية. إذا كانت صحيحة، سيتم وضع الطابع كخلفية للصفحة المطبوع عليها. بشكل افتراضي، يتم تعيينها على خطأ.
type: docs
weight: 30
url: /ar/net/aspose.pdf.facades/stamp/isbackground/
---
## خاصية Stamp.IsBackground

تحصل أو تعين حالة الخلفية. إذا كانت صحيحة، سيتم وضع الطابع كخلفية للصفحة المطبوع عليها. بشكل افتراضي، يتم تعيينها على خطأ.

```csharp
public bool IsBackground { get; set; }
```

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### انظر أيضًا

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)