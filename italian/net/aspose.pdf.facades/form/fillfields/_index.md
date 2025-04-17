---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Compila i campi della casella di testo con valori di testo e salva il documento. Rilevante per documenti firmati. Nota Applicabile solo alla casella di testo. Sia i nomi dei campi che i valori sono sensibili al maiuscolo/minuscolo.
type: docs
weight: 140
url: /it/net/aspose.pdf.facades/form/fillfields/
---
## Metodo Form.FillFields

Compila i campi della casella di testo con valori di testo e salva il documento. Rilevante per documenti firmati. Nota: Applicabile solo alla casella di testo. Sia i nomi dei campi che i valori sono sensibili al maiuscolo/minuscolo.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldNames | String[] | Nomi dei campi. |
| fieldValues | String[] | Nuovi valori dei campi. |
| output | Stream& | Stream dove il documento sarà salvato. |

### Valore di ritorno

true se i campi sono stati trovati e compilati con successo.

## Esempi

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)