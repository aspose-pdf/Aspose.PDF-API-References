---
title: "Form.FillFields"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。用文本值填充文本框字段并保存文档。适用于已签名的文档。注意仅适用于文本框。字段名称和数值均区分大小写。"
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

使用文本值填写文本框字段并保存文档。适用于已签名的文档。注意：仅适用于文本框。字段名称和数值均区分大小写。

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldNames | String[] | 字段的名称。 |
| fieldValues | String[] | 字段的新值。 |
| output | Stream& | 文档将被保存的流。 |

### 返回值

如果找到字段并成功填充，则为 true。

## 示例

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


