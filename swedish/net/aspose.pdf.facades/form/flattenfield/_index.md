---
title: "Form.FlattenField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Plattar ut ett specificerat fält med det fullständigt kvalificerade fältnamnet. Alla andra fält förblir oföränderliga. Om fältnamnet är ogiltigt förblir alla fält oföränderliga."
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

Plattar till ett specifikt fält med det fullständiga fältnamnet. Alla andra fält förblir oförändrade. Om fältnamnet är ogiltigt förblir alla fält oförändrade.

```csharp
public void FlattenField(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namnet på fältet som ska plattas ut. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


