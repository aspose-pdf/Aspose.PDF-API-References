---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Formularmethode. Füllen Sie ein Barcode-Feld gemäß seinem vollqualifizierten Feldnamen
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField-Methode

Füllen Sie ein Barcode-Feld gemäß seinem vollqualifizierten Feldnamen.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der vollqualifizierte Feldname. |
| data | String | Der neue Barcode-Wert. |

### Rückgabewert

Wenn das Füllen erfolgreich ist, wird true zurückgegeben; andernfalls false.

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)