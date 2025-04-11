---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Plattar ut ett angivet fält med det fullständiga fältnamnet. Alla andra fält förblir oförändrade. Om fieldName är ogiltigt kommer alla fält att förbli oförändrade.
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField metod

Plattar ut ett angivet fält med det fullständiga fältnamnet. Alla andra fält förblir oförändrade. Om fieldName är ogiltigt kommer alla fält att förbli oförändrade.

```csharp
public void FlattenField(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namnet på fältet som ska plattas ut. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)