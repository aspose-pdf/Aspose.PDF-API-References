---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfAnnotationEditor. Menggabungkan semua anotasi dalam dokumen
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Menggabungkan semua anotasi dalam dokumen.

```csharp
public void FlatteningAnnotations()
```

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### Lihat Juga

* kelas [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Menggabungkan semua anotasi dalam dokumen.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Menentukan mode penggabungan. |

### Lihat Juga

* kelas [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* kelas [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Menggabungkan anotasi dari tipe yang ditentukan.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| start | Int32 | Halaman awal. |
| end | Int32 | Halaman akhir. |
| annotType | AnnotationType[] | Tipe anotasi yang harus digabungkan. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Lihat Juga

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* kelas [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)