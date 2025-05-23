---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Adds new item to the list box
type: docs
weight: 120
url: /net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Adds new item to the list box.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of the field ot which new item will be added. |
| itemName | String | Name if new item. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Add a new item with Export value to the existing list box field, only for AcroForm combo box field.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of field to which items will be added. |
| exportName | String[] | A string array denoting a new list item with Export Value, i.e. (Item Label, Export Value). |

## Examples

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


