---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。用文本值填充文本框字段并保存文档。与签名文档相关。注意：仅适用于文本框。字段名称和值均区分大小写。
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields 方法

用文本值填充文本框字段并保存文档。与签名文档相关。注意：仅适用于文本框。字段名称和值均区分大小写。

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldNames | String[] | 字段名称。 |
| fieldValues | String[] | 字段的新值。 |
| output | Stream& | 文档将被保存的流。 |

### 返回值

如果找到字段并成功填充，则返回 true。

## 示例

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)