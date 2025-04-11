---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。根据其短字段名称获取完整字段名称
type: docs
weight: 250
url: /zh/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName 方法

根据其短字段名称获取完整字段名称。

```csharp
public string GetFullFieldName(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 完全限定的字段名称。 |

### 返回值

完整字段名称。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)