---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Ubah nama field
type: docs
weight: 230
url: /id/net/aspose.pdf.facades/formeditor/renamefield/
---
## Metode FormEditor.RenameField

Ubah nama field.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama lama dari field. |
| newFieldName | String | Nama baru dari field. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)