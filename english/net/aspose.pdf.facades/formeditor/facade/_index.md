---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: FormEditor property. Sets visual attributes of the field
type: docs
weight: 60
url: /net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

Sets visual attributes of the field.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Examples

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
fe.Save();
```

### See Also

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


