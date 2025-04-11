---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Ottieni la limitazione del campo di testo
type: docs
weight: 230
url: /it/net/aspose.pdf.facades/form/getfieldlimit/
---
## Metodo Form.GetFieldLimit

Ottieni la limitazione del campo di testo.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo qualificato. |

### Valore di Ritorno

Restituisce il numero massimo di caratteri che un campo di testo può contenere. Se non impostato, restituisce 0.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)