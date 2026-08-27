---
title: "Form.FillBarcodeField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Fyll i ett streckkodsfält enligt dess fullständigt kvalificerade fältnamn"
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

Fyller i ett streckkodsfält enligt dess fullständiga fältnamn.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det fullständigt kvalificerade fältnamnet. |
| data | String | Det nya streckkodsvärdet. |

### Returvärde

Om ifyllning lyckas, returnera true; annars false.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


