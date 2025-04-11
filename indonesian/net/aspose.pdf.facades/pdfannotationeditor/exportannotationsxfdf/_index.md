---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfAnnotationEditor. Mengekspor konten dari jenis anotasi yang ditentukan ke dalam XFDF
type: docs
weight: 50
url: /id/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Mengekspor konten dari jenis anotasi yang ditentukan ke dalam XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlOutputStream | Stream | Aliran XFDF keluaran. |
| start | Int32 | Halaman awal dari mana anotasi dokumen akan diekspor. |
| end | Int32 | Halaman akhir ke mana anotasi dokumen akan diekspor. |
| annotTypes | String[] | Array jenis anotasi yang perlu diekspor. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Lihat Juga

* kelas [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Mengekspor konten dari jenis anotasi yang ditentukan ke dalam XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlOutputStream | Stream | Aliran XFDF keluaran. |
| start | Int32 | Halaman awal dari mana anotasi dokumen akan diekspor. |
| end | Int32 | Halaman akhir ke mana anotasi dokumen akan diekspor. |
| annotTypes | AnnotationType[] | Array jenis anotasi yang perlu diekspor. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Lihat Juga

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* kelas [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)