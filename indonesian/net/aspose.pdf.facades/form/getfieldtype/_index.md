---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengembalikan tipe field
type: docs
weight: 240
url: /id/net/aspose.pdf.facades/form/getfieldtype/
---
## Metode Form.GetFieldType

Mengembalikan tipe field.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field. |

### Nilai Kembali

Elemen dari enumerasi FileType yang sesuai dengan tipe field.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### Lihat Juga

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)