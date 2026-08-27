---
title: "PdfAnnotationEditor.ExportAnnotationsXfdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تصدر محتوى أنواع التعليقات التوضيحية المحددة إلى XFDF"
type: docs
weight: 50
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

يصدّر محتوى الأنواع المحددة من التعليقات التوضيحية إلى XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xmlOutputStream | Stream | دفق XFDF الناتج. |
| start | Int32 | صفحة البداية التي سيتم تصدير تعليقات المستند منها. |
| end | Int32 | صفحة النهاية التي سيتم تصدير تعليقات المستند إليها. |
| annotTypes | String[] | المصفوفة التي تحتاج إلى تصدير أنواع التعليقات. |

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

يصدّر محتوى الأنواع المحددة من التعليقات التوضيحية إلى XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xmlOutputStream | Stream | دفق XFDF الناتج. |
| start | Int32 | صفحة البداية التي سيتم تصدير تعليقات المستند منها. |
| end | Int32 | صفحة النهاية التي سيتم تصدير تعليقات المستند إليها. |
| annotTypes | AnnotationType[] | المصفوفة التي تحتاج إلى تصدير أنواع التعليقات. |

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


