---
title: "FormEditor.AddListItem"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Menambahkan item baru ke list box"
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Menambahkan item baru ke list box.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang akan ditambahkan item baru. |
| itemName | String | Nama item baru. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Tambahkan item baru dengan nilai Export ke bidang list box yang ada, hanya untuk bidang combo box AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang akan ditambahkan item. |
| exportName | String[] | Array string yang menunjukkan item daftar baru dengan Nilai Ekspor, yaitu (Label Item, Nilai Ekspor). |

## Contoh

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


