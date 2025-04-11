---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengimpor konten dari field dari file fdf dan menempatkannya ke dalam pdf baru
type: docs
weight: 280
url: /id/net/aspose.pdf.facades/form/importfdf/
---
## Metode Form.ImportFdf

Mengimpor konten dari field dari file fdf dan menempatkannya ke dalam pdf baru.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFdfStream | Stream | Aliran fdf input. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)