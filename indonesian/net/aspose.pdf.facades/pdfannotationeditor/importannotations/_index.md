---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfAnnotationEditor. Mengimpor anotasi yang ditentukan ke dalam dokumen dari array dokumen PDF lainnya
type: docs
weight: 90
url: /id/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Mengimpor anotasi yang ditentukan ke dalam dokumen dari array dokumen PDF lainnya.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| annotFile | String[] | Array jalur dokumen PDF yang berisi anotasi sumber. |
| annotType | AnnotationType[] | Array tipe anotasi yang akan diimpor. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### Lihat Juga

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Mengimpor anotasi ke dalam dokumen dari array dokumen PDF lainnya.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| annotFile | String[] | Array jalur dokumen PDF yang berisi anotasi sumber. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Mengimpor anotasi yang ditentukan ke dalam dokumen dari array aliran dokumen PDF lainnya.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| annotFileStream | Stream[] | Array aliran dokumen PDF yang berisi anotasi sumber. |
| annotType | AnnotationType[] | Tipe anotasi yang akan diimpor. |

## Contoh

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

### Lihat Juga

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Mengimpor anotasi ke dalam dokumen dari array aliran dokumen PDF lainnya.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| annotFileStream | Stream[] | Array aliran dokumen PDF yang berisi anotasi sumber. |

## Contoh

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

### Lihat Juga

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)