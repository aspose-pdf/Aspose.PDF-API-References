---
title: "Form.ImportFdf"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengimpor konten bidang dari file fdf dan menempatkannya ke dalam pdf baru."
type: docs
weight: 280
url: /id/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

Mengimpor konten bidang dari file fdf dan menaruhnya ke dalam pdf baru.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFdfStream | Stream | Stream fdf input. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


