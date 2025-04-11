---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: Formularmethode. Flatten ein angegebenes Feld mit dem vollqualifizierten Feldnamen. Jedes andere Feld bleibt unveränderlich. Wenn der fieldName ungültig ist, bleiben alle Felder unveränderlich.
type: docs
weight: 170
url: /de/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField-Methode

Flatten ein angegebenes Feld mit dem vollqualifizierten Feldnamen. Jedes andere Feld bleibt unveränderlich. Wenn der fieldName ungültig ist, bleiben alle Felder unveränderlich.

```csharp
public void FlattenField(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der Name des zu flattenenden Feldes. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)