---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。获取富文本字段的值，包括每个字符的格式信息
type: docs
weight: 260
url: /zh/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText 方法

获取富文本字段的值，包括每个字符的格式信息。

```csharp
public string GetRichText(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 富文本字段的完全限定字段名称。 |

### 返回值

返回一个包含富文本字段格式信息的字符串。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)