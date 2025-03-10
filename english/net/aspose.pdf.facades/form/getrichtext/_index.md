---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Form method. Get a Rich Text fields value including the formattinf information of every character
type: docs
weight: 260
url: /net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

Get a Rich Text field's value, including the formattinf information of every character.

```csharp
public string GetRichText(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name of the Rich Text field. |

### Return Value

Return a string containing formatting information of the Rich Text field.

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


