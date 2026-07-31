---
title: "Form.GetFullFieldName"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mendapatkan nama bidang lengkap berdasarkan nama bidang pendeknya."
type: docs
weight: 250
url: /id/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

Mendapatkan nama bidang lengkap berdasarkan nama bidang pendeknya.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang sepenuhnya memenuhi kualifikasi. |

### Nilai Kembalian

Nama bidang lengkap.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


