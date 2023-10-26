---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Form method. Get the limitation of text field
type: docs
weight: 260
url: /net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

Get the limitation of text field.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |

### Return Value

Return the limitation number of characters a text field can be filled. It not set, return 0.

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


