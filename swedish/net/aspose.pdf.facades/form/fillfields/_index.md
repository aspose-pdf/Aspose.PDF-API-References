---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Fyller textlådefälten med textvärden och sparar dokumentet. Relevant för signerade dokument. Observera: Endast tillämplig på Text Box. Både fältnamn och värden är skiftlägeskänsliga.
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields metod

Fyller textlådefälten med textvärden och sparar dokumentet. Relevant för signerade dokument. Observera: Endast tillämplig på Text Box. Både fältnamn och värden är skiftlägeskänsliga.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldNames | String[] | Namn på fälten. |
| fieldValues | String[] | Nya värden för fälten. |
| output | Stream& | Stream där dokumentet kommer att sparas. |

### Returvärde

true om fälten hittades och framgångsrikt fylldes.

## Exempel

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)