---
title: "Form.GetButtonOptionValues"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。根据字段名获取单选按钮选项字段及相关值。此方法对单选按钮组有意义"
type: docs
weight: 190
url: /zh/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

根据字段名称获取单选按钮选项字段及相关值。此方法对单选按钮组有意义。

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段名称 |

### 返回值

以表单项名称为键的选项值哈希表

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


