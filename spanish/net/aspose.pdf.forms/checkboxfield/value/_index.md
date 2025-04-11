---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: Propiedad CheckboxField. Obtiene o establece el valor del campo de casilla de verificación
type: docs
weight: 70
url: /es/net/aspose.pdf.forms/checkboxfield/value/
---
## Propiedad CheckboxField.Value

Obtiene o establece el valor del campo de casilla de verificación.

```csharp
public override string Value { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo obtener y establecer el valor de una casilla de verificación de múltiples valores.

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// Allowed values may be retrieved from the AllowedStates collection
// Set the checkbox value using Value property
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// The value should be any element of AllowedStates
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Uncheck boxes by either setting Value to "Off" or setting Checked to false
checkbox.Value = "Off";
// or, alternately:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### Ver También

* clase [CheckboxField](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)