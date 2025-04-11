---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Returnerar det aktuella värdet för alternativfält för radioknappar
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue metod

Returnerar det aktuella värdet för alternativfält för radioknappar.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Fältnamn |

### Returvärde

Strängvärde för den aktuella radiogruppens alternativ. Se även [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)