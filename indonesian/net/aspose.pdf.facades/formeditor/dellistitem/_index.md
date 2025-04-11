---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Hapus item dari bidang daftar
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/formeditor/dellistitem/
---
## Metode FormEditor.DelListItem

Hapus item dari bidang daftar.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang. |
| itemName | String | Nama item yang harus dihapus. |

## Contoh

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)