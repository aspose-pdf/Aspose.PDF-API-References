---
title: "PdfAnnotationEditor.ImportAnnotationsFromXfdf"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfAnnotationEditor. Mengimpor semua anotasi dari file XFDF"
type: docs
weight: 110
url: /id/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

Mengimpor semua anotasi dari file XFDF.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xfdfFile | String | File XFDF input. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

Mengimpor semua anotasi dari aliran data XFDF.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xfdfStream | Stream | Aliran data XFDF input. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


