---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Form method. Returns type of field
type: docs
weight: 240
url: /net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType method

Returns type of field.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Field name. |

### Return Value

Element of FileType enumeration corresponding to field type.

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### See Also

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


