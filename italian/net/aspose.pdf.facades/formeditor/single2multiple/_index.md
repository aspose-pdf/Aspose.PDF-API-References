---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Cambia un campo di testo a una sola riga in uno a più righe
type: docs
weight: 350
url: /it/net/aspose.pdf.facades/formeditor/single2multiple/
---
## Metodo FormEditor.Single2Multiple

Cambia un campo di testo a una sola riga in uno a più righe.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo qualificato. |

### Valore di ritorno

Se ha successo, restituisce true; altrimenti false.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)