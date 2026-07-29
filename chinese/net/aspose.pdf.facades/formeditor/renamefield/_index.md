---
title: "FormEditor.RenameField"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。更改字段的名称"
type: docs
weight: 230
url: /zh/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

更改字段的名称。

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段的旧名称。 |
| newFieldName | String | 字段的新名称。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


