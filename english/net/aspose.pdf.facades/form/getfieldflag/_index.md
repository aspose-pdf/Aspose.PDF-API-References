---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Form method. Returns flags of the field
type: docs
weight: 250
url: /net/aspose.pdf.facades/form/getfieldflag/
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

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


