---
title: "PdfAnnotationEditor.ImportAnnotationsFromFdf"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfAnnotationEditor. Mengimpor semua anotasi dari file FDF"
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf method

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

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


