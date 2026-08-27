---
title: "Form.FillFields"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Compila i campi di casella di testo con valori di testo e salva il documento. Rilevante per documenti firmati. Nota: si applica solo alle caselle di testo. Sia il nome dei campi che i valori sono sensibili al maiuscolo/minuscolo."
type: docs
weight: 140
url: /it/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

Compila i campi casella di testo con valori testuali e salva il documento. Rilevante per documenti firmati. Nota: si applica solo a Casella di Testo. Sia il nome dei campi che i valori sono sensibili al maiuscolo/minuscolo.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldNames | String[] | Nomi dei campi. |
| fieldValues | String[] | Nuovi valori dei campi. |
| output | Stream& | Stream in cui il documento verrà salvato. |

### Valore di ritorno

true se i campi sono stati trovati e riempiti con successo.

## Esempi

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


