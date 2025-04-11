---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Fyll i ett streckkodsfält enligt dess fullständiga fältnamn
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField metod

Fyll i ett streckkodsfält enligt dess fullständiga fältnamn.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det fullständiga fältnamnet. |
| data | Sträng | Det nya streckkodsvärdet. |

### Returvärde

Om ifyllningen lyckas, returnera true; annars, false.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)