---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor method. Imports the specified annotations into document from array of another PDF documents
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Importa le annotazioni specificate nel documento da un array di altri documenti PDF.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | String[] | L'array di percorsi dei documenti PDF che contengono annotazioni sorgente. |
| annotType | AnnotationType[] | L'array dei tipi di annotazione da importare. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### See Also

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Importa annotazioni nel documento da un array di altri documenti PDF.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | String[] | L'array di percorsi dei documenti PDF che contengono annotazioni sorgente. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Importa le annotazioni specificate nel documento da un array di flussi di altri documenti PDF.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFileStream | Stream[] | L'array di flussi di documenti PDF che contengono annotazioni sorgente. |
| annotType | AnnotationType[] | I tipi di annotazione da importare. |

## Examples

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

### See Also

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Importa annotazioni nel documento da un array di flussi di altri documenti PDF.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotFileStream | Stream[] | L'array di flussi di documenti PDF che contengono annotazioni sorgente. |

## Examples

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

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)