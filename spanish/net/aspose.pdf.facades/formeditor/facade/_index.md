---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de FormEditor. Establece atributos visuales del campo
type: docs
weight: 40
url: /es/net/aspose.pdf.facades/formeditor/facade/
---
## Propiedad FormEditor.Facade

Establece atributos visuales del campo.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Ejemplos

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

### Ver También

* clase [FormFieldFacade](../../formfieldfacade/)
* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)