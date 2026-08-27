---
title: "PdfAnnotationEditor.ModifyAnnotationsAuthor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تعدل مؤلف التعليقات التوضيحية في نطاق الصفحات المحدد"
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor method

يُعدّل مؤلف التعليقات التوضيحية ضمن نطاق الصفحات المحدد.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| start | Int32 | رقم الصفحة البداية. |
| end | Int32 | رقم الصفحة النهاية. |
| srcAuthor | String | المؤلف الذي يجب تعديله. |
| desAuthor | String | المؤلف الجديد. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


