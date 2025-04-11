---
title: Page.BleedBox
second_title: Aspose.PDF for .NET API Reference
description: خاصية الصفحة. تحصل أو تعين صندوق النزيف للصفحة
type: docs
weight: 70
url: /ar/net/aspose.pdf/page/bleedbox/
---
## خاصية Page.BleedBox

تحصل أو تعين صندوق النزيف للصفحة.

```csharp
public Rectangle BleedBox { get; set; }
```

## أمثلة

المثال يوضح كيفية الحصول على صندوق النزيف للصفحة:

```csharp
Document document = new Document("sample.pdf");
Rectangle bleedBox = document.Pages[1].BleedBox;
```

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)