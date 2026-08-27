---
title: "FormEditor.DelListItem"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. حذف عنصر من حقل القائمة"
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

احذف العنصر من حقل القائمة.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل. |
| itemName | String | اسم العنصر الذي يجب حذفه. |

## أمثلة

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


