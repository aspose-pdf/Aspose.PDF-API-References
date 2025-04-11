---
title: PdfAnnotationEditor.ImportAnnotationFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Importa las anotaciones especificadas desde un archivo XFDF
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

Importa las anotaciones especificadas desde un archivo XFDF.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xfdfFile | String | El archivo XFDF de entrada. |
| annotType | AnnotationType[] | El arreglo de anotaciones que se van a importar. |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### Ver También

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

Importa las anotaciones especificadas desde un flujo de datos XFDF.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xfdfStream | Stream | El flujo de datos XFDF de entrada. |
| annotType | AnnotationType[] | El arreglo de tipos de anotaciones que se van a importar. |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### Ver También

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)