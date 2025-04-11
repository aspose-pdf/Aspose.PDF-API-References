---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Importa as anotações especificadas para o documento a partir de um array de outros documentos PDF
type: docs
weight: 90
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Importa as anotações especificadas para o documento a partir de um array de outros documentos PDF.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| annotFile | String[] | O array de caminhos de documentos PDF que contêm anotações de origem. |
| annotType | AnnotationType[] | O array de tipos de anotações a serem importados. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### Veja Também

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Importa anotações para o documento a partir de um array de outros documentos PDF.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| annotFile | String[] | O array de caminhos de documentos PDF que contêm anotações de origem. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### Veja Também

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Importa as anotações especificadas para o documento a partir de um array de streams de outros documentos PDF.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| annotFileStream | Stream[] | O array de streams de documentos PDF que contêm anotações de origem. |
| annotType | AnnotationType[] | Os tipos de anotações a serem importados. |

## Exemplos

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

### Veja Também

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Importa anotações para o documento a partir de um array de streams de outros documentos PDF.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| annotFileStream | Stream[] | O array de streams de documentos PDF que contêm anotações de origem. |

## Exemplos

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

### Veja Também

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)