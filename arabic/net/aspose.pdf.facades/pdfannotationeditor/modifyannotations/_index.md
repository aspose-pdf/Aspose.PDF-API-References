---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfAnnotationEditor. تعدل التعليقات التوضيحية من النوع المحدد على نطاق الصفحات المحدد. تدعم تعديل خصائص التعليق التوضيحي التالية: العنوان المعدل، المحتويات، اللون، الموضوع، وفتح
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## طريقة PdfAnnotationEditor.ModifyAnnotations

تعدل التعليقات التوضيحية من النوع المحدد على نطاق الصفحات المحدد. تدعم تعديل خصائص التعليق التوضيحي التالية: المعدل، العنوان، المحتويات، اللون، الموضوع، وفتح.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| start | Int32 | رقم الصفحة الابتدائية. |
| end | Int32 | رقم الصفحة النهائية. |
| annotation | Annotation | كائن التعليق التوضيحي يحتوي على خصائص جديدة. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)