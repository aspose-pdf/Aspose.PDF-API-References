---
title: "Form.GetField"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。根据字段名称获取字段的值"
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

根据字段名称获取字段的值。

```csharp
public string GetField(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完全限定的字段名称。 |

### 返回值

字段的值。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


