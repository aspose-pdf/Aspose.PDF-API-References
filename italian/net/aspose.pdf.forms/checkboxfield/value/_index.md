---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: Proprietà CheckboxField. Ottiene o imposta il valore del campo della casella di controllo
type: docs
weight: 70
url: /it/net/aspose.pdf.forms/checkboxfield/value/
---
## Proprietà CheckboxField.Value

Ottiene o imposta il valore del campo della casella di controllo.

```csharp
public override string Value { get; set; }
```

## Esempi

L'esempio dimostra come ottenere e impostare il valore di una casella di controllo a più valori.

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

### Vedi anche

* classe [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)