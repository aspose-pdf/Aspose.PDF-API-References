---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Compila un campo codice a barre secondo il suo nome di campo completamente qualificato
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Metodo Form.FillBarcodeField

Compila un campo codice a barre secondo il suo nome di campo completamente qualificato.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome di campo completamente qualificato. |
| data | String | Il nuovo valore del codice a barre. |

### Valore di Ritorno

Se la compilazione ha successo, restituisce true; altrimenti, false.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)