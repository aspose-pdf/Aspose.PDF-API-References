---
title: "Form.GetButtonOptionValues"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Ottiene i campi di opzione dei pulsanti radio e i valori correlati in base al nome del campo. Questo metodo è significativo per i gruppi di pulsanti radio"
type: docs
weight: 190
url: /it/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

Ottiene i campi opzione dei pulsanti radio e i valori correlati in base al nome del campo. Questo metodo è significativo per i gruppi di pulsanti radio.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome Campo |

### Valore di ritorno

Tabella hash dei valori di opzione indicizzati per nome dell'elemento del modulo

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


