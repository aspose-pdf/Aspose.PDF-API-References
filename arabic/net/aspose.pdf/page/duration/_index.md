---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: خاصية الصفحة. تحصل على مدة عرض الصفحة المحددة. هذه هي المدة بالثواني التي يجب عرض الصفحة خلالها أثناء العرض التقديمي. تعيد 1 إذا لم يتم تعريف المدة
type: docs
weight: 110
url: /ar/net/aspose.pdf/page/duration/
---
## خاصية Page.Duration

تحصل على مدة عرض الصفحة المحددة. هذه هي المدة بالثواني التي يجب عرض الصفحة خلالها أثناء العرض التقديمي. تعيد -1 إذا لم يتم تعريف المدة.

```csharp
public double Duration { get; set; }
```

## أمثلة

المثال يوضح كيفية الحصول على مدة الصفحة

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### انظر أيضًا

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)