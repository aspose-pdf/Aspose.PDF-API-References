---
title: "Form.FillFields"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form metod. Fyller i textrutefälten med textvärden och sparar dokumentet. Relevant för signerade dokument. Observera att det endast gäller textrutor. Både fältnamn och värden är skiftlägeskänsliga."
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

Fyller i textrutefälten med textvärden och sparar dokumentet. Relevant för signerade dokument. Obs: Gäller endast för textruta. Både fältnamnen och värdena är skiftlägeskänsliga.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldNames | String[] | Namn på fält. |
| fieldValues | String[] | Nya värden för fälten. |
| utdata | Stream& | Ström där dokumentet kommer att sparas. |

### Returvärde

true om fältet hittades och framgångsrikt fylldes.

## Exempel

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


