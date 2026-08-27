---
title: "FormEditor.RenameField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Mengubah nama field"
type: docs
weight: 230
url: /id/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

Mengubah nama field.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama lama field. |
| newFieldName | String | Nama baru field. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


