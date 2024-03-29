---
title: AddListItem
second_title: Aspose.PDF for .NET API Referansı
description: Liste kutusuna yeni öğe ekler.
type: docs
weight: 160
url: /tr/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Liste kutusuna yeni öğe ekler.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Yeni öğenin ekleneceği alanın adı. |
| itemName | String | Yeni öğe varsa adlandırın. |

### Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Ayrıca bakınız

* class [FormEditor](../../formeditor)
* ad alanı [Aspose.Pdf.Facades](../../formeditor)
* toplantı [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Varolan liste kutusu alanına, yalnızca AcroForm birleşik giriş kutusu alanı için Dışa Aktarma değeri olan yeni bir öğe ekleyin.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Öğelerin ekleneceği alanın adı. |
| exportName | String[] | Dışa Aktarma Değeri, yani (Öğe Etiketi, Dışa Aktarma Değeri) ile yeni bir liste öğesini gösteren bir dize dizisi. |

### Örnekler

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Ayrıca bakınız

* class [FormEditor](../../formeditor)
* ad alanı [Aspose.Pdf.Facades](../../formeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
