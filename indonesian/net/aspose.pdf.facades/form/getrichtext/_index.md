---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mendapatkan nilai bidang Teks Kaya termasuk informasi pemformatan dari setiap karakter
type: docs
weight: 260
url: /id/net/aspose.pdf.facades/form/getrichtext/
---
## Metode Form.GetRichText

Mendapatkan nilai bidang Teks Kaya, termasuk informasi pemformatan dari setiap karakter.

```csharp
public string GetRichText(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang Teks Kaya yang sepenuhnya memenuhi syarat. |

### Nilai Kembali

Mengembalikan string yang berisi informasi pemformatan dari bidang Teks Kaya.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)