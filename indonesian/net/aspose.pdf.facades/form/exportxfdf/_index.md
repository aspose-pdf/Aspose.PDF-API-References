---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengekspor konten dari field pdf ke dalam aliran xml. Nilai field tombol tidak akan diekspor
type: docs
weight: 90
url: /id/net/aspose.pdf.facades/form/exportxfdf/
---
## Metode Form.ExportXfdf

Mengekspor konten dari field pdf ke dalam aliran xml. Nilai field tombol tidak akan diekspor.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputXfdfStream | Stream | Aliran xml keluaran. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)