---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.XYZExplicitDestination. تمثل وجهة صريحة تعرض الصفحة مع الإحداثيات اليسار الأعلى الموجودة في الزاوية العلوية اليسرى من النافذة ومحتويات الصفحة مكبرة بعامل التكبير. قيمة فارغة لأي من المعلمات اليسار أو الأعلى أو التكبير تحدد أن القيمة الحالية لتلك المعلمة يجب أن تظل دون تغيير. قيمة التكبير 0 لها نفس معنى القيمة الفارغة
type: docs
weight: 2730
url: /ar/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class

تمثل وجهة صريحة تعرض الصفحة مع الإحداثيات (اليسار، الأعلى) الموجودة في الزاوية العلوية اليسرى من النافذة ومحتويات الصفحة مكبرة بعامل التكبير. قيمة فارغة لأي من المعلمات اليسار أو الأعلى أو التكبير تحدد أن القيمة الحالية لتلك المعلمة يجب أن تظل دون تغيير. قيمة التكبير 0 لها نفس معنى القيمة الفارغة.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | ينشئ وجهة صريحة عن بُعد. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | ينشئ وجهة صريحة محلية. |

## Properties

| Name | Description |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | يحصل على الإحداثي الأفقي الأيسر للزاوية العلوية اليسرى من النافذة. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | يحصل على كائن صفحة الوجهة |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | يحصل على رقم صفحة الوجهة |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | يحصل على الإحداثي العمودي العلوي للزاوية العلوية اليسرى من النافذة. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | يحصل على عامل التكبير. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | ينشئ وجهة إلى الموقع المحدد من الصفحة مع مراعاة دوران الصفحة إذا لزم الأمر. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | ينشئ وجهة إلى الصفحة المحددة. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | ينشئ وجهة إلى الزاوية العلوية اليسرى من الصفحة المحددة. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | يحول حالة الكائن إلى قيمة سلسلة. مثال: "1 XYZ 100 200 3". |

## Examples

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)