---
title: "Form.GetFieldLimit"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Hämta begränsningen för textfältet"
type: docs
weight: 230
url: /sv/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

Hämta begränsningen för textfältet.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |

### Returvärde

Returnerar det begränsade antalet tecken som ett textfält kan fyllas med. Om det inte är satt, returneras 0.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


