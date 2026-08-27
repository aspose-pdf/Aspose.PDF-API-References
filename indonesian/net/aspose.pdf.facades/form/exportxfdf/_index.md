---
title: "Form.ExportXfdf"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengekspor konten bidang-bidang pdf ke dalam aliran xml. Nilai bidang tombol tidak akan diekspor"
type: docs
weight: 90
url: /id/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf method

Mengekspor konten bidang pdf ke dalam aliran xml. Nilai bidang tombol tidak akan diekspor.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputXfdfStream | Stream | Aliran XML keluaran. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


