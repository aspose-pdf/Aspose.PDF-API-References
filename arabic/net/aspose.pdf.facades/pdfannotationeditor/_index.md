---
title: Class PdfAnnotationEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfAnnotationEditor class. تمثل فئة للعمل مع تعليقات توضيحية لمستندات PDF
type: docs
weight: 4410
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

تمثل فئة للعمل مع تعليقات توضيحية لمستندات PDF (تعليقات).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | يقوم بتهيئة كائن `PdfAnnotationEditor` جديد. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | يقوم بتهيئة كائن `PdfAnnotationEditor` جديد بناءً على *المستند*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يقوم بتهيئة الواجهة. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يقوم بالتخلص من Aspose.Pdf.Document المرتبط بالواجهة. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | يحذف التعليق التوضيحي بالاسم المحدد. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | يحذف جميع التعليقات التوضيحية في المستند. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | يحذف جميع التعليقات التوضيحية من النوع المحدد في المستند. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | يصدر التعليقات التوضيحية إلى التدفق. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | يصدر محتوى أنواع التعليقات التوضيحية المحددة إلى XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | يصدر محتوى أنواع التعليقات التوضيحية المحددة إلى XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | يحصل على قائمة بالتعليقات التوضيحية من الأنواع المحددة. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | يحصل على قائمة بالتعليقات التوضيحية من الأنواع المحددة. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | يقوم بتسطيح جميع التعليقات التوضيحية في المستند. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | يقوم بتسطيح جميع التعليقات التوضيحية في المستند. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | يقوم بتسطيح التعليقات التوضيحية من الأنواع المحددة. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | يستورد التعليقات التوضيحية المحددة من تدفق بيانات XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | يستورد التعليقات التوضيحية المحددة من ملف XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | يستورد التعليقات التوضيحية إلى المستند من مصفوفة من تدفقات مستندات PDF الأخرى. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | يستورد التعليقات التوضيحية إلى المستند من مصفوفة من مستندات PDF الأخرى. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | يستورد التعليقات التوضيحية المحددة إلى المستند من مصفوفة من تدفقات مستندات PDF الأخرى. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | يستورد التعليقات التوضيحية المحددة إلى المستند من مصفوفة من مستندات PDF الأخرى. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | يستورد جميع التعليقات التوضيحية من ملف FDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | يستورد جميع التعليقات التوضيحية من تدفق بيانات XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | يستورد جميع التعليقات التوضيحية من ملف XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | يعدل التعليقات التوضيحية من النوع المحدد في نطاق الصفحات المحدد. يدعم تعديل الخصائص التالية للتعليقات التوضيحية: تم التعديل، العنوان، المحتويات، اللون، الموضوع وفتح. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | يعدل مؤلف التعليقات التوضيحية في نطاق الصفحات المحدد. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | يقوم بتعتيم منطقة في الصفحة المحددة. تتم إزالة جميع المحتويات. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)