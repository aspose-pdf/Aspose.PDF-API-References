---
title: "الفئة PdfAnnotationEditor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfAnnotationEditor. تمثل فئة للعمل مع تعليقات ملاحظات مستند PDF."
type: docs
weight: 4530
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

يمثل فئة للعمل مع تعليقات توضيحية لمستند PDF (التعليقات).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | يُهيئ كائنًا جديدًا من `PdfAnnotationEditor`. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | يُهيئ كائنًا جديدًا من `PdfAnnotationEditor` على أساس *المستند*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يُهيئ الواجهة. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يفرغ Aspose.Pdf.Document المرتبط بواجهة. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | يحذف التعليق التوضيحي بالاسم المحدد. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | يحذف جميع التعليقات التوضيحية في المستند. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | يحذف جميع التعليقات التوضيحية من النوع المحدد في المستند. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | يصدّر التعليقات التوضيحية إلى تدفق. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | يصدّر محتوى الأنواع المحددة من التعليقات التوضيحية إلى XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | يصدّر محتوى الأنواع المحددة من التعليقات التوضيحية إلى XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | يحصل على قائمة التعليقات التوضيحية للأنواع المحددة. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | يحصل على قائمة التعليقات التوضيحية للأنواع المحددة. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | يُسطّح جميع التعليقات التوضيحية في المستند. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | يُسطّح جميع التعليقات التوضيحية في المستند. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | يُسطّح التعليقات التوضيحية للأنواع المحددة. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | يستورد التعليقات التوضيحية المحددة من تدفق بيانات XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | يستورد التعليقات التوضيحية المحددة من ملف XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | يستورد التعليقات التوضيحية إلى المستند من مصفوفة من تدفقات مستندات PDF أخرى. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | يستورد التعليقات التوضيحية إلى المستند من مصفوفة من مستندات PDF أخرى. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | يستورد التعليقات التوضيحية المحددة إلى المستند من مصفوفة من تدفقات مستندات PDF أخرى. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | يستورد التعليقات التوضيحية المحددة إلى المستند من مصفوفة من مستندات PDF أخرى. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | يستورد جميع التعليقات التوضيحية من ملف FDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | يستورد جميع التعليقات التوضيحية من تدفق بيانات XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | يستورد جميع التعليقات التوضيحية من ملف XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | يُعدّل التعليقات التوضيحية من النوع المحدد ضمن نطاق الصفحات المحدد. يدعم تعديل الخصائص التالية للتعليق: Modified، Title، Contents، Color، Subject و Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | يُعدّل مؤلف التعليقات التوضيحية ضمن نطاق الصفحات المحدد. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | يمحو المنطقة في الصفحة المحددة. تُزال جميع المحتويات. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


