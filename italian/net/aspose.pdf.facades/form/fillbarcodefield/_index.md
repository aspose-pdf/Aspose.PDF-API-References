---
title: FillBarcodeField
second_title: Aspose.PDF per .NET API Reference
description: Compila un campo codice a barre in base al nome del campo completo.
type: docs
weight: 150
url: /it/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

Compila un campo codice a barre in base al nome del campo completo.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo completo. |
| data | String | Il nuovo valore del codice a barre. |

### Valore di ritorno

Se il riempimento riesce, restituisce true; altrimenti falso.

### Esempi

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
