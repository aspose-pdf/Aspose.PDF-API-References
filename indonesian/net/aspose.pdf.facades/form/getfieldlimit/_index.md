---
title: "Form.GetFieldLimit"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Dapatkan batasan bidang teks"
type: docs
weight: 230
url: /id/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

Dapatkan batasan bidang teks.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang memenuhi syarat. |

### Nilai Kembalian

Kembalikan jumlah batas karakter yang dapat diisi pada bidang teks. Jika tidak disetel, kembalikan 0.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


