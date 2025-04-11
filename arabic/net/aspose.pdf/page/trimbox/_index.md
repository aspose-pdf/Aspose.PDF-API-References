---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: خاصية الصفحة. تحصل أو تعين صندوق القص للصفحة
type: docs
weight: 290
url: /ar/net/aspose.pdf/page/trimbox/
---
## خاصية Page.TrimBox

تحصل أو تعين صندوق القص للصفحة.

```csharp
public Rectangle TrimBox { get; set; }
```

## أمثلة

المثال يوضح كيفية الحصول على صندوق القص للصفحة:

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)