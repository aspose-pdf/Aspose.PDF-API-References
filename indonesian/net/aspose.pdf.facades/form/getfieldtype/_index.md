---
title: "Form.GetFieldType"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengembalikan tipe bidang"
type: docs
weight: 240
url: /id/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType method

Mengembalikan tipe bidang.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang. |

### Nilai Kembalian

Elemen enumerasi FileType yang sesuai dengan tipe bidang.

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


