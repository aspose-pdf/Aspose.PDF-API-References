---
title: "FormEditor.Items"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 属性。设置将在新创建的列表框或组合框中添加的项"
type: docs
weight: 50
url: /zh/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

设置将添加到新创建的列表框或组合框的项目。

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


