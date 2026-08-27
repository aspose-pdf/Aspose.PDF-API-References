---
title: "Form.GetField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Hämtar fältets värde enligt dess fältnamn."
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

Hämtar fältets värde enligt dess fältnamn.

```csharp
public string GetField(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det fullständigt kvalificerade fältnamnet. |

### Returvärde

Fältets värde.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


