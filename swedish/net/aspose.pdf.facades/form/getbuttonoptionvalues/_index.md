---
title: "Form.GetButtonOptionValues"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Hämtar radioknappsalternativfält och relaterade värden baserat på fältnamnet. Denna metod är relevant för radioknappsgupper"
type: docs
weight: 190
url: /sv/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

Hämtar radioknappens alternativfält och relaterade värden baserat på fältnamnet. Denna metod är relevant för radioknappgrupper.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältnamn |

### Returvärde

Hash‑tabell med alternativvärden indexerade efter formulärelementets namn

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


