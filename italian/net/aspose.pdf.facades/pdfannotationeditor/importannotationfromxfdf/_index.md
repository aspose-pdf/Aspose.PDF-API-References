---
title: ImportAnnotationFromXfdf
second_title: Aspose.PDF per .NET API Reference
description: Importa le annotazioni specificate dal file XFDF.
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

Importa le annotazioni specificate dal file XFDF.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xfdfFile | String | Il file XFDF di input. |
| annotType | AnnotationType[] | La matrice delle annotazioni da importare. |

### Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### Guarda anche

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfannotationeditor)
* assemblea [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

Importa le annotazioni specificate dal flusso di dati XFDF.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xfdfStream | Stream | Il flusso di dati XFDF di input. |
| annotType | AnnotationType[] | L'array di tipi di annotazioni da importare. |

### Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### Guarda anche

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfannotationeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->