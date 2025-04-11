---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。返回单选按钮选项字段的当前值
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue 方法

返回单选按钮选项字段的当前值。

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 字段名称 |

### 返回值

当前单选组选项的字符串值。另见 [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### 另见

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)