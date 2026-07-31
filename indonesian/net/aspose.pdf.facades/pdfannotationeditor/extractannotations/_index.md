---
title: "PdfAnnotationEditor.ExtractAnnotations"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfAnnotationEditor method. Mendapatkan daftar anotasi dari tipe yang ditentukan."
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
| annotTypes | String[] | Array tipe anotasi yang diperlukan. |

### Nilai Kembalian

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
| annotTypes | AnnotationType[] | Array tipe anotasi yang diperlukan. |

### Nilai Kembalian

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


