---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengekspor konten semua field dalam dokumen ke dalam aliran JSON. Nilai field tombol tidak diekspor
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/form/exportjson/
---
## Metode Form.ExportJson

Mengekspor konten semua field dalam dokumen ke dalam aliran JSON. Nilai field tombol tidak diekspor.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputJsonStream | Stream | Aliran JSON keluaran di mana data field dokumen akan ditulis. |
| indented | Boolean | Opsional. Menentukan apakah keluaran JSON harus diindentas untuk keterbacaan yang lebih baik. Nilai default adalah true. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)