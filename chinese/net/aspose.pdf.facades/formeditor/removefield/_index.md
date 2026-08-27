---
title: "FormEditor.RemoveField"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。从表单中移除字段"
type: docs
weight: 210
url: /zh/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

从表单中移除字段。

```csharp
public void RemoveField(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 必须移除的字段名称。 |

## 示例

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


