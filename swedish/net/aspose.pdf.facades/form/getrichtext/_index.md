---
title: "Form.GetRichText"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Hämtar ett Rich Text-fältvärde inklusive formateringsinformation för varje tecken"
type: docs
weight: 260
url: /sv/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

Hämta ett Rich Text-fälts värde, inklusive formateringsinformation för varje tecken.

```csharp
public string GetRichText(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det fullständigt kvalificerade fältnamnet för Rich Text-fältet. |

### Returvärde

Returnerar en sträng som innehåller formateringsinformation för Rich Text-fältet.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


