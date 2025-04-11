---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mendapatkan nama field lengkap sesuai dengan nama field pendeknya
type: docs
weight: 250
url: /id/net/aspose.pdf.facades/form/getfullfieldname/
---
## Metode Form.GetFullFieldName

Mendapatkan nama field lengkap sesuai dengan nama field pendeknya.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang sepenuhnya terqualified. |

### Nilai Kembali

Nama field lengkap.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)