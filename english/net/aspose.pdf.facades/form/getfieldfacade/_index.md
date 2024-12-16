---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Form method. Returns FrofmFieldFacade object containing all appearance attributes
type: docs
weight: 210
url: /net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

Returns FrofmFieldFacade object containing all appearance attributes.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of field to read. |

### Return Value

FormFieldFacade object

### See Also

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


