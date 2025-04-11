---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: CheckboxField-egenskap. Hämtar eller ställer in värdet för kryssrutan
type: docs
weight: 70
url: /sv/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value-egenskap

Hämtar eller ställer in värdet för kryssrutan.

```csharp
public override string Value { get; set; }
```

## Exempel

Exemplet visar hur man hämtar och ställer in värdet för en flervalskryssruta.

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

### Se Även

* klass [CheckboxField](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* samling [Aspose.PDF](../../../)