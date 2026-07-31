---
title: "Form.GetFieldLimit"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Ottieni la limitazione del campo di testo"
type: docs
weight: 230
url: /it/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

Ottieni la limitazione del campo di testo.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome qualificato del campo. |

### Valore di ritorno

Restituisce il numero limite di caratteri che un campo di testo può contenere. Se non impostato, restituisce 0.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


