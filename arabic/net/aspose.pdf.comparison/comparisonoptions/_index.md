---
title: "الفئة ComparisonOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Comparison.ComparisonOptions. تمثل فئة خيارات مقارنة مستند PDF."
type: docs
weight: 3260
url: /ar/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class

يمثّل فئة خيارات مقارنة PDF document.

```csharp
public class ComparisonOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | يحصل على ترتيب عمليات التحرير أو يضبطه. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | احصل على مناطق الاستبعاد أو عيّنها. تُستخدم للصفحة الأولى أو المستند في طريقة المقارنة. يمكن ضبط هذا الخيار مع [`ExcludeTables`](./excludetables/). لا يمكن ضبط هذا الخيار مع خيار [`ExtractionArea`](./extractionarea/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | احصل على مناطق الاستبعاد أو عيّنها. تُستخدم للصفحة الثانية أو المستند في طريقة المقارنة. يمكن ضبط هذا الخيار مع [`ExcludeTables`](./excludetables/). لا يمكن ضبط هذا الخيار مع خيار [`ExtractionArea`](./extractionarea/). |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | احصل على الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة أو عينه. لا يمكن ضبط هذا الخيار مع خيار [`ExtractionArea`](./extractionarea/). القيمة الافتراضية هي `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | احصل على المنطقة المستطيلة التي سيتم مقارنة نص الصفحات داخلها أو عينها. لا يمكن ضبط هذا الخيار مع خيارات [`ExcludeTables`](./excludetables/)، [`ExcludeAreas1`](./excludeareas1/) و[`ExcludeAreas2`](./excludeareas2/). |

### انظر أيضًا

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


