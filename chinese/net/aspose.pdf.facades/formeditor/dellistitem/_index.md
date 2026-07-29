---
title: "FormEditor.DelListItem"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。删除列表字段中的项目"
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

从列表字段中删除项。

```csharp
public void DelListItem(string fieldName, string itemName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段的名称。 |
| itemName | String | 必须删除的项目名称。 |

## 示例

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


