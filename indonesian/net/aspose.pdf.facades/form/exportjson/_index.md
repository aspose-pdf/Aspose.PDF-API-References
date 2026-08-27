---
title: "Form.ExportJson"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengekspor isi semua bidang dalam dokumen ke aliran JSON. Nilai bidang tombol tidak diekspor"
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

Mengekspor isi semua bidang dalam dokumen ke aliran JSON. Nilai bidang tombol tidak diekspor.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputJsonStream | Stream | Aliran JSON output tempat data bidang dokumen akan ditulis. |
| diindent | Boolean | Opsional. Menentukan apakah output JSON harus diindent untuk meningkatkan keterbacaan. Nilai default adalah true. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


