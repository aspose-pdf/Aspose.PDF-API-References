---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Form method. Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups
type: docs
weight: 220
url: /net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Field Name |

### Return Value

Hash table of option values keyed by form item name

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


