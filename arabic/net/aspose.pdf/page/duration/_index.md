---
title: "Page.Duration"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Page. تحصل أو تعين مدة عرض الصفحة. هذه هي الوقت بالثواني التي يجب عرض الصفحة خلالها أثناء العرض. تُعيد 1 إذا لم تُحدد المدة."
type: docs
weight: 110
url: /ar/net/aspose.pdf/page/duration/
---
## Page.Duration property

يحصل أو يضبط مدة عرض الصفحة. هذه هي الوقت بالثواني التي يجب عرض الصفحة خلالها أثناء العرض. يُرجع -1 إذا لم يتم تعريف المدة.

```csharp
public double Duration { get; set; }
```

## أمثلة

يوضح المثال كيفية الحصول على مدة الصفحة

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### انظر أيضًا

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


