---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfAnnotationEditor. Importe les annotations spécifiées dans le document à partir d'un tableau d'autres documents PDF
type: docs
weight: 90
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Importe les annotations spécifiées dans le document à partir d'un tableau d'autres documents PDF.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| annotFile | String[] | Le tableau des chemins des documents PDF contenant les annotations source. |
| annotType | AnnotationType[] | Le tableau des types d'annotations à importer. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### Voir aussi

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Importe des annotations dans le document à partir d'un tableau d'autres documents PDF.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| annotFile | String[] | Le tableau des chemins des documents PDF contenant les annotations source. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Importe les annotations spécifiées dans le document à partir d'un tableau de flux d'autres documents PDF.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| annotFileStream | Stream[] | Le tableau des flux de documents PDF contenant les annotations source. |
| annotType | AnnotationType[] | Les types d'annotations à importer. |

## Exemples

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

### Voir aussi

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Importe des annotations dans le document à partir d'un tableau de flux d'autres documents PDF.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| annotFileStream | Stream[] | Le tableau des flux de documents PDF contenant les annotations source. |

## Exemples

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

### Voir aussi

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)