---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。获取文本字段的限制
type: docs
weight: 230
url: /zh/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit 方法

获取文本字段的限制。

```csharp
public int GetFieldLimit(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 合格的字段名称。 |

### 返回值

返回文本字段可以填写的字符限制数。如果未设置，则返回 0。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)