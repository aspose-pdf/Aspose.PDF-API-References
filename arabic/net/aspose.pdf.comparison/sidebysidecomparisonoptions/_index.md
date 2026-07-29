---
title: "الفئة SideBySideComparisonOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Comparison.SideBySideComparisonOptions. تمثل فئة خيارات لمقارنة المستندات مع إخراج جنبًا إلى جنب."
type: docs
weight: 3400
url: /ar/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

يمثّل فئة خيارات لمقارنة documents مع مخرجات جنبًا إلى جنب.

```csharp
public class SideBySideComparisonOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | احصل على الخاصية التي تحدد ما إذا كانت علامات التغيير الإضافية معروضة أو عيّنها. إذا تم ضبطها، تُظهر علامات التغيير التي ليست في الصفحة الحالية ولكنها موجودة في صفحة أخرى. إذا كان التغيير يقع بين الكلمات، قد لا تكون العلامة موضوعة بدقة بالنسبة إلى حرف المسافة. القيمة الافتراضية هي `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | احصل على وتعيين منطقة المقارنة. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. لا يمكن تعيين هذا الخيار مع خيارات [`ExcludeTables`](./excludetables/)، [`ExcludeAreas1`](./excludeareas1/) و[`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | احصل على وتعيين منطقة المقارنة. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. لا يمكن تعيين هذا الخيار مع خيارات [`ExcludeTables`](./excludetables/)، [`ExcludeAreas1`](./excludeareas1/) و[`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | احصل على وتعيين وضع المقارنة. القيمة الافتراضية هي !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | احصل على وتعيين مناطق الاستبعاد. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. يمكن تعيين هذا الخيار مع [`ExcludeTables`](./excludetables/). لا يمكن تعيين هذا الخيار مع خيار [`ComparisonArea1`](./comparisonarea1/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | احصل على وتعيين مناطق الاستبعاد. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. يمكن تعيين هذا الخيار مع [`ExcludeTables`](./excludetables/). لا يمكن تعيين هذا الخيار مع خيار [`ComparisonArea2`](./comparisonarea2/). |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | احصل على وتعيين الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة. لا يمكن تعيين هذا الخيار مع [`ComparisonArea1`](./comparisonarea1/) و[`ComparisonArea2`](./comparisonarea2/). القيمة الافتراضية هي `false`. |

### انظر أيضًا

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


