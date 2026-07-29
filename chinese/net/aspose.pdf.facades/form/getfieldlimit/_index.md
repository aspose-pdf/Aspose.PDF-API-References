---
title: "Form.GetFieldLimit"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。获取文本字段的限制"
type: docs
weight: 230
url: /zh/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

获取文本字段的限制。

```csharp
public int GetFieldLimit(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完整的字段名称。 |

### 返回值

返回文本字段可填写的字符数限制。如果未设置，则返回 0。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


