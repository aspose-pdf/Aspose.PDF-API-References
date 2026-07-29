---
title: "Form.GetButtonOptionCurrentValue"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。返回单选按钮选项字段的当前值"
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue method

返回单选按钮选项字段的当前值。

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段名称 |

### 返回值

当前单选组的字符串值。另请参阅 [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


