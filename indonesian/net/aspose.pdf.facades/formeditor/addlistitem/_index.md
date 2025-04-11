---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Menambahkan item baru ke dalam kotak daftar
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Menambahkan item baru ke dalam kotak daftar.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field di mana item baru akan ditambahkan. |
| itemName | String | Nama item baru. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Menambahkan item baru dengan nilai Ekspor ke field kotak daftar yang sudah ada, hanya untuk field kotak kombinasi AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field di mana item akan ditambahkan. |
| exportName | String[] | Array string yang menunjukkan item daftar baru dengan Nilai Ekspor, yaitu (Label Item, Nilai Ekspor). |

## Contoh

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)