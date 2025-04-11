---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengembalikan flag dari field
type: docs
weight: 220
url: /id/net/aspose.pdf.facades/form/getfieldflag/
---
## Metode Form.GetFieldFlag

Mengembalikan flag dari field.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field |

### Nilai Kembali

Flag properti (ReadOnly/ Required/NoExport

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### Lihat Juga

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)