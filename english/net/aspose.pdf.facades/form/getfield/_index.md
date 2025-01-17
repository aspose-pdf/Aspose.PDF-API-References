---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Form method. Gets the fields value according to its field name
type: docs
weight: 200
url: /net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

Gets the field's value according to its field name.

```csharp
public string GetField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name. |

### Return Value

The field's value.

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


