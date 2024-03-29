---
title: FillFields
second_title: Aspose.PDF per .NET API Reference
description: Riempie i campi della casella di testo con valori di testo e salva il documento. Rilevante per i documenti firmati. Avviso applicabile solo alla casella di testo. Sia il nome che i valori dei campi fanno distinzione tra maiuscole e minuscole.
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

Riempie i campi della casella di testo con valori di testo e salva il documento. Rilevante per i documenti firmati. Avviso: applicabile solo alla casella di testo. Sia il nome che i valori dei campi fanno distinzione tra maiuscole e minuscole.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldNames | String[] | Nomi dei campi. |
| fieldValues | String[] | Nuovi valori dei campi. |
| output | Stream& | Stream in cui verrà salvato il documento. |

### Valore di ritorno

true se i campi sono stati trovati e compilati correttamente.

### Esempi

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
