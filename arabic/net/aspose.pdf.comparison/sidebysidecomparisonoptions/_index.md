---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Comparison.SideBySideComparisonOptions. تمثل فئة خيارات لمقارنة الوثائق مع إخراج جنبًا إلى جنب
type: docs
weight: 3290
url: /ar/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## فئة خيارات المقارنة جنبًا إلى جنب

تمثل فئة خيارات لمقارنة الوثائق مع إخراج جنبًا إلى جنب.

```csharp
public class SideBySideComparisonOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | احصل على الخاصية وقم بتعيينها التي تحدد ما إذا كانت علامات التغيير الإضافية معروضة. إذا تم تعيينها، تعرض علامات التغيير التي ليست على الصفحة الحالية ولكنها موجودة في صفحة أخرى. إذا كانت التغييرات تقع بين الكلمات، قد لا تكون العلامة موضوعة بدقة بالنسبة إلى حرف المسافة. القيمة الافتراضية هي `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | احصل على منطقة المقارنة وقم بتعيينها. تستخدم للصفحة أو الوثيقة الأولى في طريقة المقارنة. لا يمكن تعيين هذا الخيار مع خيارات [`ExcludeTables`](./excludetables/)، [`ExcludeAreas1`](./excludeareas1/) و [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | احصل على منطقة المقارنة وقم بتعيينها. تستخدم للصفحة أو الوثيقة الثانية في طريقة المقارنة. لا يمكن تعيين هذا الخيار مع خيارات [`ExcludeTables`](./excludetables/)، [`ExcludeAreas1`](./excludeareas1/) و [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | يحصل على وضع المقارنة ويقوم بتعيينه. القيمة الافتراضية هي !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | احصل على المناطق المستبعدة وقم بتعيينها. تستخدم للصفحة أو الوثيقة الأولى في طريقة المقارنة. يمكن تعيين هذا الخيار مع [`ExcludeTables`](./excludetables/). لا يمكن تعيين هذا الخيار مع خيار [`ComparisonArea1`](./comparisonarea1/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | احصل على المناطق المستبعدة وقم بتعيينها. تستخدم للصفحة أو الوثيقة الثانية في طريقة المقارنة. يمكن تعيين هذا الخيار مع [`ExcludeTables`](./excludetables/). لا يمكن تعيين هذا الخيار مع خيار [`ComparisonArea2`](./comparisonarea2/). |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | احصل على الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة. لا يمكن تعيين هذا الخيار مع [`ComparisonArea1`](./comparisonarea1/) و [`ComparisonArea2`](./comparisonarea2/). القيمة الافتراضية هي `false`. |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* التجميع [Aspose.PDF](../../)