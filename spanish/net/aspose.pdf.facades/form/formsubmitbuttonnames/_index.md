---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Propiedad del formulario. Obtiene todos los nombres de los botones de envío del formulario
type: docs
weight: 40
url: /es/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Propiedad Form.FormSubmitButtonNames

Obtiene todos los nombres de los botones de envío del formulario.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)