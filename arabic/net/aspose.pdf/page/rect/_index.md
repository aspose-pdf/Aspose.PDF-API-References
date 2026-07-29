---
title: "Page.Rect"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Page. تُحصل أو تُعيّن مستطيل الصفحة. عند الاستعلام يتم إرجاع صندوق القص إذا تم تحديده وإلا يتم إرجاع صندوق الوسائط للصفحة. عند التعيين يتم دائمًا تعيين صندوق الوسائط للصفحة. يرجى ملاحظة أن هذه الخاصية لا تأخذ دوران الصفحة في الاعتبار. للحصول على مستطيل الصفحة مع مراعاة الدوران يرجى استخدام ActualRect"
type: docs
weight: 230
url: /ar/net/aspose.pdf/page/rect/
---
## Page.Rect property

يحصل أو يضبط مستطيل الصفحة. عند الحصول: يتم إرجاع صندوق القص إذا تم تحديده، وإلا يتم إرجاع صندوق الوسائط. عند الضبط: يتم دائمًا ضبط صندوق الوسائط. يرجى ملاحظة أن هذه الخاصية لا تأخذ دوران الصفحة في الاعتبار. للحصول على مستطيل الصفحة مع مراعاة الدوران يرجى استخدام ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## أمثلة

يوضح المثال كيفية الحصول على مستطيل الصفحة:

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


