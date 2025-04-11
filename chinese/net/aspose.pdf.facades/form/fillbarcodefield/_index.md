---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。根据其完全限定的字段名称填写条形码字段
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField 方法

根据其完全限定的字段名称填写条形码字段。

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 完全限定的字段名称。 |
| data | 字符串 | 新的条形码值。 |

### 返回值

如果填写成功，返回 true；否则，返回 false。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)