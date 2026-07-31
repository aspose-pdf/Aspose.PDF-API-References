---
title: "FormEditor.RemoveFieldAction"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "FormEditor method. Menghapus aksi submit dari field."
type: docs
weight: 220
url: /id/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction method

Menghapus aksi submit field.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


