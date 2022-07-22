---
title: PdfAnnotationEditor
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة للعمل مع التعليقات التوضيحية لمستند PDF .
type: docs
weight: 2420
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

يمثل فئة للعمل مع التعليقات التوضيحية لمستند PDF .

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor#constructor)() | تهيئة جديد[`PdfAnnotationEditor`](../pdfannotationeditor) الكائن . |
| [PdfAnnotationEditor](pdfannotationeditor#constructor_1)(Document) | تهيئة جديد[`PdfAnnotationEditor`](../pdfannotationeditor) كائن على قاعدة*document* . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | تهيئة الواجهة . |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Disposes Aspose.Pdf. وثيقة مرتبطة بواجهة . |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation)(string) | حذف التعليق التوضيحي باسم التعليق التوضيحي المحدد. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations)() | حذف كافة التعليقات التوضيحية في المستند. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations_1)(string) | حذف كافة التعليقات التوضيحية من النوع المحدد في المستند. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf)(Stream) | يصدر التعليقات التوضيحية إلى البث . |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | تصدير محتوى أنواع التعليقات التوضيحية المحددة إلى XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf_1)(Stream, int, int, string[]) | تصدير محتوى أنواع التعليقات التوضيحية المحددة إلى XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations)(int, int, AnnotationType[]) | الحصول على قائمة التعليقات التوضيحية للأنواع المحددة. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations_1)(int, int, string[]) | الحصول على قائمة التعليقات التوضيحية للأنواع المحددة. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations)() | لتسوية جميع التعليقات التوضيحية في المستند. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_1)(FlattenSettings) | لتسوية جميع التعليقات التوضيحية في المستند. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_2)(int, int, AnnotationType[]) | لتسوية التعليقات التوضيحية للأنواع المحددة. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_1)(Stream, AnnotationType[]) | يستورد التعليقات التوضيحية المحددة من تدفق بيانات XFDF . |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_3)(string, AnnotationType[]) | يستورد التعليقات التوضيحية المحددة من ملف XFDF . |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations)(Stream[]) | يقوم باستيراد التعليقات التوضيحية في المستند من مصفوفة تدفق مستند PDF آخر. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_2)(string[]) | يستورد التعليقات التوضيحية في مستند من مصفوفة مستندات PDF أخرى. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_1)(Stream[], AnnotationType[]) | يستورد التعليقات التوضيحية المحددة في المستند من مصفوفة تدفق مستند PDF آخر. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_3)(string[], AnnotationType[]) | يستورد التعليقات التوضيحية المحددة في المستند من مصفوفة مستندات PDF أخرى. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | يستورد كل التعليقات التوضيحية من دفق بيانات XFDF . |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | يستورد كل التعليقات التوضيحية من ملف XFDF . |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations#modifyannotations)(int, int, Annotation) | يعدل التعليقات التوضيحية للنوع المحدد في نطاق الصفحات المحدد. وهو يدعم تعديل خصائص التعليق التوضيحي التالية: التعديل والعنوان والمحتويات واللون والموضوع والفتح. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor)(int, int, string, string) | تعديل كاتب التعليقات التوضيحية في نطاق الصفحات المحدد. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea)(int, Rectangle, Color) | منطقة التنقيح في الصفحة المحددة. تتم إزالة كافة المحتويات. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | يحفظ مستند PDF في التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | يحفظ مستند PDF في الملف المحدد. |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
