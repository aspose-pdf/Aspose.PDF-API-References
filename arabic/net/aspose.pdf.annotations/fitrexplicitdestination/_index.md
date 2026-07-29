---
title: "الفئة FitRExplicitDestination"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Annotations.FitRExplicitDestination. تمثل وجهة صريحة تعرض الصفحة بمحتوياتها مكبرة بما يكفي لتلائم المستطيل المحدد بالإحداثيات اليسار، الأسفل، اليمين، والأعلى بالكامل داخل النافذة أفقياً وعمودياً. إذا كانت عوامل التكبير الأفقية والعمودية المطلوبة مختلفة، استخدم الأصغر منهما مع توسيط المستطيل داخل النافذة في البعد الآخر. قد يؤدي قيمة null لأي من المعلمات إلى سلوك غير متوقع."
type: docs
weight: 1870
url: /ar/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class

يمثل الوجهة الصريحة التي تعرض الصفحة مع تكبير محتواها بما يكفي لتلائم المستطيل المحدد بالإحداثيات اليسار، الأسفل، اليمين، والعلوي بالكامل داخل النافذة أفقياً وعمودياً. إذا كانت عوامل التكبير الأفقية والعمودية المطلوبة مختلفة، استخدم الأصغر منهما، مع تمركز المستطيل داخل النافذة في البُعد الآخر. قد يؤدي قيمة null لأي من المعاملات إلى سلوك غير متوقع.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | ينشئ وجهة صريحة عن بُعد. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | ينشئ وجهة صريحة محلية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | يحصل على الإحداثي العمودي السفلي للمستطيل المرئي. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | يحصل على الإحداثي الأفقي الأيسر للمستطيل المرئي. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | يحصل على كائن صفحة الوجهة |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | يحصل على رقم صفحة الوجهة |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | يحصل على الإحداثي الأفقي الأيمن للمستطيل المرئي. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | يحصل على الإحداثي العمودي العلوي للمستطيل المرئي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | يحوّل حالة الكائن إلى قيمة نصية. مثال: "1 FitR 100 200 300 400". |

### انظر أيضًا

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


