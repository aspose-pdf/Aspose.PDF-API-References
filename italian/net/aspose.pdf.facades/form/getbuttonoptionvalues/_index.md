---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Ottiene i campi delle opzioni dei pulsanti radio e i valori correlati in base al nome del campo. Questo metodo ha significato per i gruppi di pulsanti radio
type: docs
weight: 190
url: /it/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Metodo Form.GetButtonOptionValues

Ottiene i campi delle opzioni dei pulsanti radio e i valori correlati in base al nome del campo. Questo metodo ha significato per i gruppi di pulsanti radio.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo |

### Valore di ritorno

Tabella hash dei valori delle opzioni indicizzati per nome dell'elemento del modulo

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)