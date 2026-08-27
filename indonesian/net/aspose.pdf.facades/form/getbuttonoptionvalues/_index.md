---
title: "Form.GetButtonOptionValues"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. Metode ini berguna untuk grup tombol radio"
type: docs
weight: 190
url: /id/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

Mendapatkan bidang opsi tombol radio dan nilai terkait berdasarkan nama bidang. Metode ini berguna untuk grup tombol radio.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama Bidang |

### Nilai Kembalian

Tabel hash nilai opsi yang diindeks oleh nama item formulir

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


