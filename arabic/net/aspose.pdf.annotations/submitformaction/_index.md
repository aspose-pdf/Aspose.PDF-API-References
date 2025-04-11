---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.SubmitFormAction. فئة تصف إجراء submitform
type: docs
weight: 2640
url: /ar/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

فئة تصف إجراء submit-form.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Constructors

| Name | Description |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | يقوم بتهيئة كائن SubmitFormAction. |

## Properties

| Name | Description |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | يحصل أو يحدد علامات إجراء الإرسال |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | الإجراءات التالية في التسلسل. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | عنوان URL الوجهة. |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | يحصل على سلسلة لإجراء ECMAScript. |

## Fields

| Name | Description |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | إذا تم تعيينه، يجب تحويل أي قيم حقل تم تقديمها تمثل تواريخ إلى التنسيق القياسي. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | إذا تم تعيينه، يجب أن تكون إدخال F من FDF المقدم مواصفة ملف تحتوي على دفق ملف مضمن يمثل ملف PDF الذي يتم تقديم FDF منه. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | إذا تم تعيينه، يجب أن يستبعد FDF المقدم إدخال F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | إذا تم تعيينه، يجب أن يتضمن فقط تلك التعليقات التوضيحية التي تتطابق إدخال T الخاصة بها مع اسم المستخدم الحالي. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | إذا تم إلغاء تحديده، يحدد مصفوفة Fields الحقول التي يجب تضمينها في الإرسال. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | إذا تم تعيينه، يجب تقديم أسماء الحقول والقيم بتنسيق نموذج HTML. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | إذا تم تعيينه، يجب تقديم أسماء الحقول والقيم باستخدام طلب HTTP GET. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | إذا تم تعيينه، يجب أن يتضمن ملف FDF المقدم جميع التعليقات التوضيحية في مستند PDF الأساسي. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | إذا تم تعيينه، يجب أن يتضمن ملف FDF المقدم محتويات جميع التحديثات التزايدية. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | إذا تم تعيينه، يجب تقديم جميع الحقول المحددة بواسطة مصفوفة Fields وعلم Include/Exclude. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | إذا تم تعيينه، يجب نقل إحداثيات نقرة الماوس التي تسببت في إجراء submit-form كجزء من بيانات النموذج. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | إذا تم تعيينه، يجب تقديم المستند كملف PDF، باستخدام نوع محتوى MIME application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | إذا تم تعيينه، يجب تقديم أسماء الحقول والقيم كـ XFDF. |

### See Also

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)