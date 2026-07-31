---
title: "CheckboxField.Value"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà CheckboxField. Ottiene o imposta il valore del campo casella di controllo"
type: docs
weight: 70
url: /it/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value property

Ottiene o imposta il valore del campo casella di controllo.

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

// I valori consentiti possono essere recuperati dalla collezione AllowedStates
// Imposta il valore della casella di controllo utilizzando la proprietà Value
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// Il valore deve essere un qualsiasi elemento di AllowedStates
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Deseleziona le caselle impostando Value su "Off" o impostando Checked su false
checkbox.Value = "Off";
// oppure, alternativamente:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### Vedi anche

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


