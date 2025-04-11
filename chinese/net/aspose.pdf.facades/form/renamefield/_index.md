---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。重命名字段。可以是 AcroForm 字段或 XFA 字段
type: docs
weight: 330
url: /zh/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField 方法

重命名字段。可以是 AcroForm 字段或 XFA 字段。

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 旧字段名称 |
| newFieldName | 字符串 | 新字段名称 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)