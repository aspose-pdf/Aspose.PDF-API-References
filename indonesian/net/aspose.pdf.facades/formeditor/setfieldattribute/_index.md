---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Atur atribut bidang
type: docs
weight: 290
url: /id/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## Metode FormEditor.SetFieldAttribute

Atur atribut bidang.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang atributnya harus diatur. |
| flag | PropertyFlag | Flag (NoExport/ReadOnly/Required) |

### Nilai Kembali

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