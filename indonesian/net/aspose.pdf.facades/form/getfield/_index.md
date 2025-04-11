---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mendapatkan nilai field sesuai dengan nama field-nya
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/form/getfield/
---
## Metode Form.GetField

Mendapatkan nilai field sesuai dengan nama field-nya.

```csharp
public string GetField(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang sepenuhnya terqualifikasi. |

### Nilai Kembali

Nilai field.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)