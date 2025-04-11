---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。将单行文本字段更改为多行文本字段
type: docs
weight: 350
url: /zh/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple 方法

将单行文本字段更改为多行文本字段。

```csharp
public bool Single2Multiple(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 合格的字段名称。 |

### 返回值

如果成功，返回 true；否则返回 false。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)