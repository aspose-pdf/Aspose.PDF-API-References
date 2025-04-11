---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: 表单属性。获取表单上的字段名称列表
type: docs
weight: 30
url: /zh/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames 属性

获取表单上的字段名称列表。

```csharp
public string[] FieldNames { get; }
```

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### 另见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)