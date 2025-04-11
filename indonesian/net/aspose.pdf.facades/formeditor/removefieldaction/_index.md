---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Hapus aksi kirim dari field
type: docs
weight: 220
url: /id/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## Metode FormEditor.RemoveFieldAction

Hapus aksi kirim dari field.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama dari field. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)