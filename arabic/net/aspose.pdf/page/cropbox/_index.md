---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: خاصية الصفحة. تحصل أو تعين صندوق القص للصفحة
type: docs
weight: 100
url: /ar/net/aspose.pdf/page/cropbox/
---
## خاصية Page.CropBox

تحصل أو تعين صندوق القص للصفحة.

```csharp
public Rectangle CropBox { get; set; }
```

## أمثلة

المثال يوضح كيفية الحصول على صندوق القص للصفحة:

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)