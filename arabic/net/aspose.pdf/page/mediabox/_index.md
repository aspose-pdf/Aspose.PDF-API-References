---
title: Page.MediaBox
second_title: Aspose.PDF for .NET API Reference
description: خاصية الصفحة. تحصل أو تعين صندوق الوسائط للصفحة
type: docs
weight: 180
url: /ar/net/aspose.pdf/page/mediabox/
---
## خاصية Page.MediaBox

تحصل أو تعين صندوق الوسائط للصفحة.

```csharp
public Rectangle MediaBox { get; set; }
```

## أمثلة

المثال يوضح كيفية الحصول على صندوق الوسائط للصفحة:

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)