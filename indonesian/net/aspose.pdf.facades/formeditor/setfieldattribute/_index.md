---
title: "FormEditor.SetFieldAttribute"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Mengatur atribut field"
type: docs
weight: 290
url: /id/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute method

Mengatur atribut field.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang atributnya harus diatur. |
| flag | PropertyFlag | Flag (NoExport/ReadOnly/Required) |

### Nilai Kembalian

true jika atribut berhasil diatur.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Lihat Juga

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


