---
title: "Form.GetRichText"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。获取富文本字段的值，包含每个字符的格式信息。"
type: docs
weight: 260
url: /zh/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

获取 Rich Text 字段的值，包括每个字符的格式信息。

```csharp
public string GetRichText(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 富文本字段的完全限定字段名称。 |

### 返回值

返回包含富文本字段格式信息的字符串。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


