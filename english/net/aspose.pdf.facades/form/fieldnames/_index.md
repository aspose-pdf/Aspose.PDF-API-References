---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Form property. Gets list of field names on the form
type: docs
weight: 30
url: /net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames property

Gets list of field names on the form.

```csharp
public string[] FieldNames { get; }
```

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


