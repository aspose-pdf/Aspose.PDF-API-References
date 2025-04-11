---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: Propriété CheckboxField. Obtient ou définit la valeur du champ de case à cocher
type: docs
weight: 70
url: /fr/net/aspose.pdf.forms/checkboxfield/value/
---
## Propriété CheckboxField.Value

Obtient ou définit la valeur du champ de case à cocher.

```csharp
public override string Value { get; set; }
```

## Exemples

L'exemple démontre comment obtenir et définir la valeur d'une case à cocher à valeurs multiples.

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

### Voir aussi

* classe [CheckboxField](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)