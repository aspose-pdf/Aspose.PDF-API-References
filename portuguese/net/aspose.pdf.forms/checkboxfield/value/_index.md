---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: Propriedade CheckboxField. Obtém ou define o valor do campo de caixa de seleção
type: docs
weight: 70
url: /pt/net/aspose.pdf.forms/checkboxfield/value/
---
## Propriedade CheckboxField.Value

Obtém ou define o valor do campo de caixa de seleção.

```csharp
public override string Value { get; set; }
```

## Exemplos

O exemplo demonstra como obter e definir o valor de uma caixa de seleção de múltiplos valores.

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

### Veja Também

* classe [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)