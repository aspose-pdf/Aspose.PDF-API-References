---
title: "FormEditor.AddListItem"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. إضافة عنصر جديد إلى صندوق القائمة"
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

يضيف عنصرًا جديدًا إلى صندوق القائمة.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي سيُضاف إليه العنصر الجديد. |
| itemName | String | اسم العنصر الجديد. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

إضافة عنصر جديد بقيمة تصدير إلى حقل صندوق القائمة الموجود، فقط لحقل صندوق القائمة المنسدلة في AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي ستُضاف إليه العناصر. |
| exportName | String[] | مصفوفة سلاسل تمثل عنصر قائمة جديد مع قيمة التصدير، أي (تسمية العنصر، قيمة التصدير). |

## أمثلة

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


