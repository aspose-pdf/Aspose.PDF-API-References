---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。更改字段名称
type: docs
weight: 230
url: /zh/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField 方法

更改字段名称。

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 字段的旧名称。 |
| newFieldName | 字符串 | 字段的新名称。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)