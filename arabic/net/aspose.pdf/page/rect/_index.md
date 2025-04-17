---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: خاصية الصفحة. تحصل أو تعين مستطيل الصفحة. للحصول على يتم إرجاع صندوق قص الصفحة إذا تم تحديده، وإلا يتم إرجاع صندوق وسائط الصفحة. للتعيين يتم دائمًا تعيين صندوق وسائط الصفحة. يرجى ملاحظة أن هذه الخاصية لا تأخذ في الاعتبار دوران الصفحة. للحصول على مستطيل الصفحة مع مراعاة الدوران، يرجى استخدام ActualRect.
type: docs
weight: 230
url: /ar/net/aspose.pdf/page/rect/
---
## خاصية Page.Rect

تحصل أو تعين مستطيل الصفحة. للحصول على: يتم إرجاع صندوق قص الصفحة إذا تم تحديده، وإلا يتم إرجاع صندوق وسائط الصفحة. للتعيين: يتم دائمًا تعيين صندوق وسائط الصفحة. يرجى ملاحظة أن هذه الخاصية لا تأخذ في الاعتبار دوران الصفحة. للحصول على مستطيل الصفحة مع مراعاة الدوران، يرجى استخدام ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## أمثلة

المثال يوضح كيفية الحصول على مستطيل الصفحة:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### انظر أيضًا

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)