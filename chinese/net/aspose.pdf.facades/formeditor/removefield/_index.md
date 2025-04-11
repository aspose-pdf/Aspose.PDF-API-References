---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。 从表单中移除字段
type: docs
weight: 210
url: /zh/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField 方法

从表单中移除字段。

```csharp
public void RemoveField(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 必须移除的字段名称。 |

## 示例

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### 另请参见

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)