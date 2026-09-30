---
title: "Form.GetFieldFlag"
linktitle: "GetFieldFlag"
articleTitle: "GetFieldFlag"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Returns flags of the field."
type: docs
weight: 370
url: "/net/aspose.pdf.facades/form/getfieldflag/"
product_version: "26.9.0"
---
## Form.GetFieldFlag method

Returns flags of the field.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Field name |

### Return Value

Property flag (ReadOnly/ Required/NoExport

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### See Also

* enum [PropertyFlag](../../../aspose.pdf.facades/propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

