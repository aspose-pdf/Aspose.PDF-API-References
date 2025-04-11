---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfAnnotationEditor. تعدل مؤلف التعليقات التوضيحية على نطاق الصفحات المحدد
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## طريقة PdfAnnotationEditor.ModifyAnnotationsAuthor

تعدل مؤلف التعليقات التوضيحية على نطاق الصفحات المحدد.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| start | Int32 | رقم الصفحة الابتدائية. |
| end | Int32 | رقم الصفحة النهائية. |
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