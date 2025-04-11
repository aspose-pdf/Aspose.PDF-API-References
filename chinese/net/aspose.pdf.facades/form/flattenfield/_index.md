---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。使用完全限定的字段名称扁平化指定字段。其他字段将保持不变。如果 fieldName 无效，所有字段将保持不变。
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField 方法

使用完全限定的字段名称扁平化指定字段。其他字段将保持不变。如果 fieldName 无效，所有字段将保持不变。

```csharp
public void FlattenField(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 要扁平化的字段名称。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)