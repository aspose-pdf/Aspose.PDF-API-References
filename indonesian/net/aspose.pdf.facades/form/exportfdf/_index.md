---
title: "Form.ExportFdf"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengekspor konten bidang-bidang pdf ke dalam aliran fdf"
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf method

Mengekspor konten bidang pdf ke dalam aliran fdf.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFdfStream | Stream | Aliran fdf output. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


