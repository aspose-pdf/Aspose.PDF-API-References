---
title: Items
second_title: Aspose.PDF for .NET API 参考
description: 设置将添加到单独创建的列表框或组合框的项目
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

设置将添加到单独创建的列表框或组合框的项目。

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### 也可以看看

* class [FormEditor](../../formeditor)
* 命名空间 [Aspose.Pdf.Facades](../../formeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
