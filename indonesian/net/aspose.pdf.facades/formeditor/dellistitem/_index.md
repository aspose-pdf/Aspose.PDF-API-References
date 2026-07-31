---
title: "FormEditor.DelListItem"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "FormEditor method. Menghapus item dari field daftar"
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

Menghapus item dari field daftar.

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


