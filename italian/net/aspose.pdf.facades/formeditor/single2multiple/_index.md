---
title: Single2Multiple
second_title: Aspose.PDF per .NET API Reference
description: Modifica un campo di testo a riga singola in uno a più righe.
type: docs
weight: 390
url: /it/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

Modifica un campo di testo a riga singola in uno a più righe.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo qualificato. |

### Valore di ritorno

Se ha successo, restituisce true; altrimenti false.

### Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Guarda anche

* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->