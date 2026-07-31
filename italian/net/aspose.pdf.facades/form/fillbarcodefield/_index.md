---
title: "Form.FillBarcodeField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Compila un campo barcode in base al suo nome di campo completamente qualificato"
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

Compila un campo barcode in base al suo nome campo completamente qualificato.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome completo del campo. |
| data | String | Il nuovo valore del barcode. |

### Valore di ritorno

Se la compilazione ha successo, restituisce true; altrimenti, false.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


