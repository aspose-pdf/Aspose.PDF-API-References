---
title: "Form.GetFieldFacade"
linktitle: "GetFieldFacade"
articleTitle: "GetFieldFacade"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Returns FrofmFieldFacade object containing all appearance attributes. Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form(\"form.pdf\"); Fo..."
type: docs
weight: 130
url: "/net/aspose.pdf.facades/form/getfieldfacade/"
product_version: "26.9.0"
---
## GetFieldFacade(string) {#getfieldfacade}

Returns FrofmFieldFacade object containing all appearance attributes.
 
 Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
 FormFieldFacade field = form.GetFieldFacade("field1");
 Console.WriteLine("Color of field border: " + field.BorderColor);

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | string | Name of field to read. |

### Return Value

[FormFieldFacade](../../../aspose.pdf.facades/formfieldfacade/)

FormFieldFacade object

### See Also

* class [FormFieldFacade](../../../aspose.pdf.facades/formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

