---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Hapus field dari formulir
type: docs
weight: 210
url: /id/net/aspose.pdf.facades/formeditor/removefield/
---
## Metode FormEditor.RemoveField

Hapus field dari formulir.

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

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)