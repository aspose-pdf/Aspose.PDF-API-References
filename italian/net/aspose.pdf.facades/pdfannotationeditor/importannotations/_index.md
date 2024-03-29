---
title: ImportAnnotations
second_title: Aspose.PDF per .NET API Reference
description: Importa le annotazioni specificate nel documento dallarray di altri documenti PDF.
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Importa le annotazioni specificate nel documento dall'array di altri documenti PDF.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| annotFile | String[] | L'array di percorsi di documenti PDF che contengono annotazioni di origine. |
| annotType | AnnotationType[] | L'array di tipi di annotazioni da importare. |

### Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### Guarda anche

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfannotationeditor)
* assemblea [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Importa le annotazioni nel documento dall'array di altri documenti PDF.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| annotFile | String[] | L'array di percorsi di documenti PDF che contengono annotazioni di origine. |

### Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfannotationeditor)
* assemblea [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Importa le annotazioni specificate nel documento dall'array di un altro flusso di documenti PDF.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| annotFileStream | Stream[] | L'array di flussi di documenti PDF che contengono annotazioni di origine. |
| annotType | AnnotationType[] | I tipi di annotazione da importare. |

### Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
stream[0]= File.OpenRead("with_annots1.pdf");
stream[1]= File.OpenRead("with_annots2.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(streams, annotTypes);
editor.Save("example_out.pdf");
stream[0].Close();
stream[1].Close();
```

### Guarda anche

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfannotationeditor)
* assemblea [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Importa le annotazioni nel documento dall'array di un altro flusso di documenti PDF.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| annotFileStream | Stream[] | L'array di flussi di documenti PDF che contengono annotazioni di origine. |

### Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
streams[0]= File.OpenRead("with_annots1.pdf");
streams[1]= File.OpenRead("with_annots2.pdf");
editor.ImportAnnotations(streams);
editor.Save("example_out.pdf");
streams[0].Close();
streams[1].Close();
```

### Guarda anche

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfannotationeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
