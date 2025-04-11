---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Comparison.ComparisonOptions. تمثل فئة خيارات مقارنة مستند PDF
type: docs
weight: 3150
url: /ar/net/aspose.pdf.comparison/comparisonoptions/
---
## فئة خيارات المقارنة

تمثل فئة خيارات مقارنة مستند PDF.

```csharp
public class ComparisonOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | يحصل على ويضبط ترتيب عمليات التحرير. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | يحصل على ويضبط المناطق المستبعدة. يستخدم للصفحة الأولى أو المستند في طريقة المقارنة. يمكن ضبط هذا الخيار مع [`ExcludeTables`](./excludetables/). لا يمكن ضبط هذا الخيار مع خيار [`ExtractionArea`](./extractionarea/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | يحصل على ويضبط المناطق المستبعدة. يستخدم للصفحة الثانية أو المستند في طريقة المقارنة. يمكن ضبط هذا الخيار مع [`ExcludeTables`](./excludetables/). لا يمكن ضبط هذا الخيار مع خيار [`ExtractionArea`](./extractionarea/). |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | يحصل على ويضبط الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة. لا يمكن ضبط هذا الخيار مع خيار [`ExtractionArea`](./extractionarea/). القيمة الافتراضية هي `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | يحصل على ويضبط المنطقة المستطيلة التي سيتم مقارنة نص الصفحات فيها. لا يمكن ضبط هذا الخيار مع خيارات [`ExcludeTables`](./excludetables/)، [`ExcludeAreas1`](./excludeareas1/) و [`ExcludeAreas2`](./excludeareas2/). |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* التجميع [Aspose.PDF](../../)