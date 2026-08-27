---
title: "FormEditor.ExportItems"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 属性。设置带有导出值的组合框选项"
type: docs
weight: 30
url: /zh/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems property

设置带有导出值的组合框选项。

```csharp
public string[][] ExportItems { get; set; }
```

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
formEditor.ExportItems = new string[][] 
{ 
    new string[] { "1", "Firs" }, 
    new string[] { "2", "Second" }, 
    new string[] { "3", "Third" } 
};
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


