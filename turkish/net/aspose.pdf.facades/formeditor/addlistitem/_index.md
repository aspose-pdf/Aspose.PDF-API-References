---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Liste kutusuna yeni öğe ekler
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Liste kutusuna yeni öğe ekler.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Yeni öğenin ekleneceği alanın adı. |
| itemName | String | Yeni öğenin adı. |

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Ayrıca Bakınız

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Mevcut liste kutusu alanına, yalnızca AcroForm kombinasyon kutusu alanı için, Export değeri ile yeni bir öğe ekler.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Öğelerin ekleneceği alanın adı. |
| exportName | String[] | Export Değeri ile yeni bir liste öğesini belirten bir dize dizisi, yani (Öğe Etiketi, Export Değeri). |

## Örnekler

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Ayrıca Bakınız

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)