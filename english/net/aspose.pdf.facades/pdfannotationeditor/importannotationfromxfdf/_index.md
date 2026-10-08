---
title: "PdfAnnotationEditor.ImportAnnotationFromXfdf"
linktitle: "ImportAnnotationFromXfdf"
articleTitle: "ImportAnnotationFromXfdf"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfAnnotationEditor method. Imports the specified annotations from XFDF file."
type: docs
weight: 50
url: "/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/"
product_version: "26.9"
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf}

Imports the specified annotations from XFDF file.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | String | The input XFDF file. |
| annotType | AnnotationType[] | The annotations array to be imported. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### See Also

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

Imports the specified annotations from XFDF data stream.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfStream | Stream | The input XFDF data stream. |
| annotType | AnnotationType[] | The array of annotation types to be imported. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### See Also

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

