---
title: "الفئة SubmitFormAction"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Annotations.SubmitFormAction. فئة تصف إجراء submitform."
type: docs
weight: 2740
url: /ar/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

الفئة التي تصف إجراء إرسال-نموذج.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | يُنشئ كائن SubmitFormAction. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | يحصل أو يعيّن العلامات لإجراء الإرسال. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | الإجراءات التالية في التسلسل. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | عنوان URL الوجهة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | يحصل على النص لإجراء ECMAScript. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | إذا تم الضبط، سيتم تحويل أي قيم حقول مُرسَلة تمثّل تواريخ إلى الصيغة القياسية. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | إذا تم الضبط، يجب أن يكون إدخال F في FDF المُرسَل مواصفة ملف تحتوي على تدفق ملف مدمج يمثل ملف PDF الذي يُرسل منه FDF. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | إذا تم الضبط، يجب أن يستثني FDF المُرسَل إدخال F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | إذا تم الضبط، يجب أن يتضمن فقط تعليقات الترميز التي يطابق إدخال T فيها اسم المستخدم الحالي. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | إذا لم يتم الضبط، تحدد مصفوفة Fields الحقول التي يجب تضمينها في الإرسال. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | إذا تم الضبط، سيتم إرسال أسماء الحقول وقيمها بتنسيق نموذج HTML. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | إذا تم الضبط، سيتم إرسال أسماء الحقول وقيمها باستخدام طلب HTTP GET. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | إذا تم تعيينه، يجب أن يتضمن ملف FDF المرسل جميع تعليقات العلامات التوضيحية في مستند PDF الأساسي. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | إذا تم تعيينه، يجب أن يتضمن ملف FDF المرسل محتويات جميع التحديثات المتزايدة. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | إذا تم تعيينه، يجب إرسال جميع الحقول المحددة بواسطة مصفوفة Fields وعلم Include/Exclude. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | إذا تم تعيينه، يجب نقل إحداثيات نقرة الفأرة التي تسببت في إجراء submit-form كجزء من بيانات النموذج. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | إذا تم تعيينه، يجب إرسال المستند كـ PDF باستخدام نوع محتوى MIME application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | إذا تم تعيينه، يجب إرسال أسماء الحقول والقيم كـ XFDF. |

### انظر أيضًا

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


