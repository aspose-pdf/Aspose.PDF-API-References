---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Hämtar fältets värde enligt dess fältnamn
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField metod

Hämtar fältets värde enligt dess fältnamn.

```csharp
public string GetField(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det fullständigt kvalificerade fältnamnet. |

### Returvärde

Fältets värde.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)