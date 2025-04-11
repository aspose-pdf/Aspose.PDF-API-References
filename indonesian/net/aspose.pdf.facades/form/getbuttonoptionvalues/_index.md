---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengambil bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. Metode ini memiliki arti untuk grup tombol radio
type: docs
weight: 190
url: /id/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Metode Form.GetButtonOptionValues

Mengambil bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. Metode ini memiliki arti untuk grup tombol radio.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama Bidang |

### Nilai Kembali

Tabel hash nilai opsi yang dikunci berdasarkan nama item formulir

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)