---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。返回字段类型
type: docs
weight: 240
url: /zh/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType 方法

返回字段类型。

```csharp
public FieldType GetFieldType(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 字段名称。 |

### 返回值

与字段类型对应的 FileType 枚举元素。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### 另请参阅

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)