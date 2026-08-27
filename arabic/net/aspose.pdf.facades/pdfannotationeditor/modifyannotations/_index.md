---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تعدل التعليقات من النوع المحدد في نطاق الصفحات المحدد. يدعم تعديل الخصائص التالية للتعليق: Modified Title Contents Color Subject و Open."
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

يُعدّل التعليقات التوضيحية من النوع المحدد ضمن نطاق الصفحات المحدد. يدعم تعديل الخصائص التالية للتعليق: Modified، Title، Contents، Color، Subject و Open.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| start | Int32 | رقم الصفحة البداية. |
| end | Int32 | رقم الصفحة النهاية. |
| annotation | Annotation | كائن التعليق يحتوي على خصائص جديدة. |

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


