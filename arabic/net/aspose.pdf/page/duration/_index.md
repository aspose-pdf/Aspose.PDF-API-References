---
title: Duration
second_title: Aspose.PDF لمرجع .NET API
description: الحصول على مدة عرض الصفحة المحددة. هذا هو الوقت بالثواني الذي سيتم عرض هذه الصفحة أثناء العرض التقديمي . Returs -1 إذا لم يتم تحديد المدة.
type: docs
weight: 110
url: /ar/net/aspose.pdf/page/duration/
---
## Page.Duration property

الحصول على مدة عرض الصفحة المحددة. هذا هو الوقت بالثواني الذي سيتم عرض هذه الصفحة أثناء العرض التقديمي . Returs -1 إذا لم يتم تحديد المدة.

```csharp
public double Duration { get; set; }
```

### أمثلة

مثال يوضح كيفية الحصول على مدة الصفحة

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### أنظر أيضا

* class [Page](../../page)
* مساحة الاسم [Aspose.Pdf](../../page)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
