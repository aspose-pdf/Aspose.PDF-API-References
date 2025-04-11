---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfAnnotationEditor. Mengimpor semua anotasi dari file FDF
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## Metode PdfAnnotationEditor.ImportAnnotationsFromFdf

Mengimpor semua anotasi dari file FDF.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fdfFile | String | File FDF input. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)