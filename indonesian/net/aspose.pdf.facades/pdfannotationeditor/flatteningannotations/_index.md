---
title: "PdfAnnotationEditor.FlatteningAnnotations"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfAnnotationEditor metode. Mengflatten semua anotasi dalam dokumen"
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

Menyatukan semua anotasi dalam dokumen.

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

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

Menyatukan semua anotasi dalam dokumen.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Menentukan mode flattening. |

### Lihat Juga

* class [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

Menyatukan anotasi dari tipe yang ditentukan.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| start | Int32 | Halaman awal. |
| end | Int32 | Kemudian halaman akhir. |
| annotType | AnnotationType[] | Tipe anotasi harus di-flatten. |

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
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


