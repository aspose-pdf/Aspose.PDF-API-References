---
title: "الفئة XYZExplicitDestination"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Annotations.XYZExplicitDestination class. يمثل وجهة صريحة تعرض الصفحة مع إحداثيات اليسار العلوي موضوعة في الزاوية العليا اليسرى للنافذة ومحتويات الصفحة مكبرة بمعامل التكبير. قيمة null لأي من المعلمات اليسار أو العلوية أو التكبير تشير إلى أن القيمة الحالية لتلك المعلمة يجب الاحتفاظ بها دون تغيير. قيمة التكبير 0 لها نفس معنى قيمة null."
type: docs
weight: 2830
url: /ar/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class

يمثل الوجهة الصريحة التي تعرض الصفحة بالإحداثيات (اليسار، الأعلى) الموضوعة في الزاوية العلوية اليسرى للنافذة ومحتوى الصفحة مكبرًا بمعامل التكبير. قيمة فارغة لأي من المعلمات اليسار أو الأعلى أو التكبير تشير إلى أن القيمة الحالية لتلك المعلمة يجب الاحتفاظ بها دون تغيير. قيمة التكبير 0 لها نفس معنى القيمة الفارغة.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | ينشئ وجهة صريحة عن بُعد. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | ينشئ وجهة صريحة محلية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | يحصل على الإحداثي الأفقي الأيسر للزاوية العليا اليسرى للنافذة. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | يحصل على كائن صفحة الوجهة |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | يحصل على رقم صفحة الوجهة |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | يحصل على الإحداثي العمودي العلوي للزاوية العليا اليسرى للنافذة. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | يحصل على معامل التكبير. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | إنشاء وجهة إلى الموقع المحدد للصفحة مع مراعاة دوران الصفحة إذا لزم الأمر. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | إنشاء وجهة إلى الصفحة المحددة. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | إنشاء وجهة إلى الزاوية العليا اليسرى للصفحة المحددة. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | يحوّل حالة الكائن إلى قيمة نصية. مثال: "1 XYZ 100 200 3". |

## أمثلة

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### انظر أيضًا

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


