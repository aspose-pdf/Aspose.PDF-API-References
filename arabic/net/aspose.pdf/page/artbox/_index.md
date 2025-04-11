---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: خاصية الصفحة. تحصل أو تعين صندوق الفن للصفحة
type: docs
weight: 30
url: /ar/net/aspose.pdf/page/artbox/
---
## خاصية Page.ArtBox

تحصل أو تعين صندوق الفن للصفحة.

```csharp
public Rectangle ArtBox { get; set; }
```

## أمثلة

المثال يوضح كيفية الحصول على صندوق الفن للصفحة:

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)