---
title: "Form.GetButtonOptionCurrentValue"
linktitle: "GetButtonOptionCurrentValue"
articleTitle: "GetButtonOptionCurrentValue"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Returns the current value for radio button option fields."
type: docs
weight: 100
url: "/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/"
product_version: "26.9.0"
---
## Form.GetButtonOptionCurrentValue method

Returns the current value for radio button option fields.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Field Name |

### Return Value

String value for the current radio group optino. See also `GetButtonOptionValues`

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

