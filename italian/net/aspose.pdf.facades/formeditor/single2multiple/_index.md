---
title: "FormEditor.Single2Multiple"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Cambia un campo di testo a riga singola in uno a più righe"
type: docs
weight: 350
url: /it/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

Modifica un campo di testo a riga singola in uno a più righe.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome qualificato del campo. |

### Valore di ritorno

Se ha successo, restituisce true; altrimenti false.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


