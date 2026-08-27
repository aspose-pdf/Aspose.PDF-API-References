---
title: "FormEditor.RemoveField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Menghapus field dari formulir"
type: docs
weight: 210
url: /id/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

Menghapus field dari formulir.

```csharp
public void RemoveField(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang harus dihapus. |

## Contoh

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


