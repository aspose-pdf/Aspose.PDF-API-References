---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. Belirtilen not türlerinin içeriğini XFDF'ye aktarır
type: docs
weight: 50
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Belirtilen not türlerinin içeriğini XFDF'ye aktarır

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlOutputStream | Stream | Çıktı XFDF akışı. |
| start | Int32 | Notların belgeden aktarılacağı başlangıç sayfası. |
| end | Int32 | Notların belgeden aktarılacağı bitiş sayfası. |
| annotTypes | String[] | Aktarılması gereken not türlerinin dizisi. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Ayrıca Bakınız

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Belirtilen not türlerinin içeriğini XFDF'ye aktarır

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlOutputStream | Stream | Çıktı XFDF akışı. |
| start | Int32 | Notların belgeden aktarılacağı başlangıç sayfası. |
| end | Int32 | Notların belgeden aktarılacağı bitiş sayfası. |
| annotTypes | AnnotationType[] | Aktarılması gereken not türlerinin dizisi. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Ayrıca Bakınız

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)