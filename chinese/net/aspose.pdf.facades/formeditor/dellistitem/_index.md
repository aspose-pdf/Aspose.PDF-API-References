---
title: DelListItem
second_title: Aspose.PDF for .NET API 参考
description: 从列表字段中删除项目
type: docs
weight: 220
url: /zh/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

从列表字段中删除项目。

```csharp
public void DelListItem(string fieldName, string itemName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段的名称。 |
| itemName | String | 必须删除的项目的名称。 |

### 例子

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### 也可以看看

* class [FormEditor](../../formeditor)
* 命名空间 [Aspose.Pdf.Facades](../../formeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->