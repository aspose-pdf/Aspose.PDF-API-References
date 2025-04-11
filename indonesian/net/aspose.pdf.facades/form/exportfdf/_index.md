---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengekspor konten dari field pdf ke dalam aliran fdf
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/form/exportfdf/
---
## Metode Form.ExportFdf

Mengekspor konten dari field pdf ke dalam aliran fdf.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFdfStream | Stream | Aliran fdf keluaran. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)