---
title: "Form.GetFieldFlag"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengembalikan flag bidang"
type: docs
weight: 220
url: /id/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag method

Mengembalikan flag bidang.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang |

### Nilai Kembalian

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


