---
title: "Form.FillBarcodeField"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。根据其完全限定字段名填充条形码字段"
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

根据其完全限定字段名填写条形码字段。

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完全限定的字段名称。 |
| data | String | 新的条形码值。 |

### 返回值

如果填充成功，返回 true；否则返回 false。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


