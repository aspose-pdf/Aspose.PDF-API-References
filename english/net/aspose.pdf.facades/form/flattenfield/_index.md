---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: Form method. Flattens a specified field with the fully qualified field name. Any other field will remain unchangable. If the fieldName is invalid all the fields will remain unchangable
type: docs
weight: 170
url: /net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

Flattens a specified field with the fully qualified field name. Any other field will remain unchangable. If the fieldName is invalid, all the fields will remain unchangable.

```csharp
public void FlattenField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The name of the field to be flattened. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


