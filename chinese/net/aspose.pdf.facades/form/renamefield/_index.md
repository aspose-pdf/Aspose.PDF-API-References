---
title: "Form.RenameField"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。重命名字段。AcroForm 字段或 XFA 字段均可。"
type: docs
weight: 330
url: /zh/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

重命名字段。AcroForm 字段或 XFA 字段均可。

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 旧字段名 |
| newFieldName | String | 新字段名 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


