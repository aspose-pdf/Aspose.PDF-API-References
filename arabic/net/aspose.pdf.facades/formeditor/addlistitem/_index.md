---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تضيف عنصرًا جديدًا إلى مربع القائمة
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

تضيف عنصرًا جديدًا إلى مربع القائمة.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي سيتم إضافة عنصر جديد إليه. |
| itemName | String | اسم العنصر الجديد. |

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

أضف عنصرًا جديدًا بقيمة تصدير إلى حقل مربع القائمة الموجود، فقط لحقل مربع الجمع في AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي ستتم إضافة العناصر إليه. |
| exportName | String[] | مصفوفة سلسلة تشير إلى عنصر قائمة جديد مع قيمة تصدير، أي (تسمية العنصر، قيمة التصدير). |

## Examples

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)