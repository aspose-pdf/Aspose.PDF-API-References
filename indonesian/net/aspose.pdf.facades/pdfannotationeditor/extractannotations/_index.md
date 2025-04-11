---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfAnnotationEditor. Mendapatkan daftar anotasi dari tipe yang ditentukan
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Mendapatkan daftar anotasi dari tipe yang ditentukan.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| start | Int32 | Halaman awal dari mana anotasi akan dipilih. |
| end | Int32 | Halaman akhir ke mana anotasi akan dipilih. |
| annotTypes | String[] | Array dari tipe anotasi yang dibutuhkan. |

### Return Value

Daftar anotasi.

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Lihat Juga

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Mendapatkan daftar anotasi dari tipe yang ditentukan.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| start | Int32 | Halaman awal dari mana anotasi akan dipilih. |
| end | Int32 | Halaman akhir ke mana anotasi akan dipilih. |
| annotTypes | AnnotationType[] | Array dari tipe anotasi yang dibutuhkan. |

### Return Value

Daftar anotasi.

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Lihat Juga

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)