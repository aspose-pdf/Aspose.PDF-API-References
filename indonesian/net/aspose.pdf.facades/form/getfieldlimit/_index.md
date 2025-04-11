---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mendapatkan batasan dari field teks
type: docs
weight: 230
url: /id/net/aspose.pdf.facades/form/getfieldlimit/
---
## Metode Form.GetFieldLimit

Mendapatkan batasan dari field teks.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang memenuhi syarat. |

### Nilai Kembali

Mengembalikan jumlah karakter batasan yang dapat diisi dalam field teks. Jika tidak diatur, mengembalikan 0.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)