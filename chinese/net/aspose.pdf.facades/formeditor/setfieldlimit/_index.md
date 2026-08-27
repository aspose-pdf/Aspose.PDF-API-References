---
title: "FormEditor.SetFieldLimit"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。设置文本字段的最大字符数。"
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

设置文本字段的最大字符数。

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 文本字段的名称。 |
| fieldLimit | Int32 | 字段限制的新值。 |

### 返回值

如果成功设置字段限制，则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


