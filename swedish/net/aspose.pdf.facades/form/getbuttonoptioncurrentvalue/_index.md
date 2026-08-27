---
title: "Form.GetButtonOptionCurrentValue"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Returnerar det aktuella värdet för alternativfält för radioknappar."
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue method

Returnerar det aktuella värdet för radioknappsalternativfält.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältnamn |

### Returvärde

Strängvärde för den aktuella radiogruppens alternativ. Se även [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


