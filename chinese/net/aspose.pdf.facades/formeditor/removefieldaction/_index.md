---
title: "FormEditor.RemoveFieldAction"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。移除字段的提交操作。"
type: docs
weight: 220
url: /zh/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction method

移除字段的提交操作。

```csharp
public void RemoveFieldAction(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段的名称。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


