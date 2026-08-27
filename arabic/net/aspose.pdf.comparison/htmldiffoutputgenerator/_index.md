---
title: "الفئة HtmlDiffOutputGenerator"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Comparison.HtmlDiffOutputGenerator class. تمثل فئة لتوليد تمثيل html لاختلافات النصوص. يتم الإشارة إلى فواصل الأسطر المحذوفة بعلامة الفقرة"
type: docs
weight: 3310
url: /ar/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

يمثّل فئة لإنشاء تمثيل html لاختلافات النصوص. يتم الإشارة إلى فواصل الأسطر المحذوفة بعلامة الفقرة.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | ينشئ مثيلًا من الفئة `HtmlDiffOutputGenerator`. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | ينشئ مثيلًا من الفئة `HtmlDiffOutputGenerator`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | يحصل على سلسلة نمط CSS لعملية الحذف ويضبطها. مثال: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | يحصل على سلسلة نمط CSS لعملية المساواة ويضبطها. مثال: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | يحصل على سلسلة نمط CSS لعملية الإدراج ويضبطها. مثال: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | احصل أو اضبط نمط text-decoration: line-through لعملية الحذف. القيمة الافتراضية هي `False`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | ينشئ المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | ينشئ المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | ينشئ المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | ينشئ المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |

### انظر أيضًا

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


