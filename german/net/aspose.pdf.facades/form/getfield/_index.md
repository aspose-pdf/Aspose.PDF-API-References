---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Holt den Wert des Feldes entsprechend seinem Feldnamen
type: docs
weight: 200
url: /de/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField-Methode

Holt den Wert des Feldes entsprechend seinem Feldnamen.

```csharp
public string GetField(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der vollqualifizierte Feldname. |

### Rückgabewert

Der Wert des Feldes.

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)