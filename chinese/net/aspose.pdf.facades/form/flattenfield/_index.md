---
title: "Form.FlattenField"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。使用完全限定字段名将指定字段扁平化。其他字段保持不变。如果字段名无效，所有字段都保持不变。"
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

使用完全限定字段名扁平化指定字段。其他字段将保持不可更改。如果 fieldName 无效，所有字段将保持不可更改。

```csharp
public void FlattenField(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 要展平的字段名称。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


