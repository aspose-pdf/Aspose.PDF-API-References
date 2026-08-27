---
title: "CheckboxField.Value"
second_title: "Aspose.PDF för .NET API‑referens"
description: "CheckboxField-egenskap. Hämtar eller anger värdet för kryssrutan."
type: docs
weight: 70
url: /sv/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value property

Hämtar eller anger värde för kryssruta.

```csharp
public override string Value { get; set; }
```

## Exempel

Exemplet visar hur man hämtar och sätter värdet för en kryssruta med flera värden.

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// Tillåtna värden kan hämtas från samlingen AllowedStates.
// Ställ in kryssrutans värde med egenskapen Value.
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// Värdet bör vara ett element i AllowedStates.
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Avmarkera rutor genom att antingen sätta Value till "Off" eller sätta Checked till false.
checkbox.Value = "Off";
// eller, alternativt:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### Se även

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


