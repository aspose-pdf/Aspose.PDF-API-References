---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Form method. Gets the full field name according to its short field name
type: docs
weight: 250
url: /net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

Gets the full field name according to its short field name.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name. |

### Return Value

The full field name.

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


