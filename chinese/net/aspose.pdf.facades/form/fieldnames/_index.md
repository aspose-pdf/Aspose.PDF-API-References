---
title: "Form.FieldNames"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 属性。获取表单上字段名称的列表。"
type: docs
weight: 30
url: /zh/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames property

获取表单上字段名称的列表。

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

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


