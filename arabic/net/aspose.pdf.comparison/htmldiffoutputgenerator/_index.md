---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.HtmlDiffOutputGenerator class. تمثل فئة لتوليد تمثيل HTML لاختلافات النصوص. يتم الإشارة إلى فواصل الأسطر المحذوفة بواسطة علامة الفقرة
type: docs
weight: 3200
url: /ar/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

تمثل فئة لتوليد تمثيل HTML لاختلافات النصوص. يتم الإشارة إلى فواصل الأسطر المحذوفة بواسطة علامة الفقرة.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | ينشئ مثيلًا من فئة `HtmlDiffOutputGenerator`. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | ينشئ مثيلًا من فئة `HtmlDiffOutputGenerator`. |

## Properties

| Name | Description |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | يحصل على سلسلة نمط CSS لعملية الحذف ويضبطها. مثال: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | يحصل على سلسلة نمط CSS لعملية المساواة ويضبطها. مثال: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | يحصل على سلسلة نمط CSS لعملية الإدراج ويضبطها. مثال: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | يحصل أو يضبط نمط text-decoration: line-through لعملية الحذف. القيمة الافتراضية هي `False`. |

## Methods

| Name | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | يولد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | يولد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | يولد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | يولد المخرجات بناءً على الاختلافات بين النصوص ويحفظها في ملف. |

### See Also

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)