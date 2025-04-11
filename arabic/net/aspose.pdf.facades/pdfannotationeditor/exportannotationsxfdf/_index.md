---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfAnnotationEditor. تصدر محتوى أنواع التعليقات المحددة إلى XFDF
type: docs
weight: 50
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

تصدر محتوى أنواع التعليقات المحددة إلى XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlOutputStream | Stream | تدفق XFDF الناتج. |
| start | Int32 | الصفحة التي ستصدر منها تعليقات المستند. |
| end | Int32 | الصفحة التي ستصدر إليها تعليقات المستند. |
| annotTypes | String[] | مصفوفة أنواع التعليقات التي تحتاج إلى التصدير. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

تصدر محتوى أنواع التعليقات المحددة إلى XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlOutputStream | Stream | تدفق XFDF الناتج. |
| start | Int32 | الصفحة التي ستصدر منها تعليقات المستند. |
| end | Int32 | الصفحة التي ستصدر إليها تعليقات المستند. |
| annotTypes | AnnotationType[] | مصفوفة أنواع التعليقات التي تحتاج إلى التصدير. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### انظر أيضًا

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)