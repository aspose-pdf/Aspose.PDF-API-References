---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。 从列表字段中删除项目
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem 方法

从列表字段中删除项目。

```csharp
public void DelListItem(string fieldName, string itemName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 字段的名称。 |
| itemName | 字符串 | 必须删除的项目名称。 |

## 示例

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### 另请参见

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)