---
title: "Form.GetFullFieldName"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。根据其短字段名称获取完整字段名称"
type: docs
weight: 250
url: /zh/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

根据其短字段名获取完整字段名。

```csharp
public string GetFullFieldName(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完全限定的字段名称。 |

### 返回值

完整字段名称。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


