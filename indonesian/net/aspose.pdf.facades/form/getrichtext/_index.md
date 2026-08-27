---
title: "Form.GetRichText"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mendapatkan nilai bidang Rich Text termasuk informasi pemformatan setiap karakter"
type: docs
weight: 260
url: /id/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

Dapatkan nilai bidang Rich Text, termasuk informasi pemformatan setiap karakter.

```csharp
public string GetRichText(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang Rich Text yang sepenuhnya memenuhi syarat. |

### Nilai Kembalian

Mengembalikan string yang berisi informasi pemformatan bidang Rich Text.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


