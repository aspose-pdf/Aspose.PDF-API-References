---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengembalikan nilai saat ini untuk bidang opsi tombol radio
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Metode Form.GetButtonOptionCurrentValue

Mengembalikan nilai saat ini untuk bidang opsi tombol radio.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama Bidang |

### Nilai Kembali

Nilai string untuk opsi grup radio saat ini. Lihat juga [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)