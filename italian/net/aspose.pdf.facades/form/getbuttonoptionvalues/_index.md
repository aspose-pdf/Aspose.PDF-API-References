---
title: GetButtonOptionValues
second_title: Aspose.PDF per .NET API Reference
description: Ottiene i campi delle opzioni del pulsante di opzione e i valori correlati in base al nome del campo. Questo metodo ha significato per i gruppi di pulsanti di opzione.
type: docs
weight: 220
url: /it/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

Ottiene i campi delle opzioni del pulsante di opzione e i valori correlati in base al nome del campo. Questo metodo ha significato per i gruppi di pulsanti di opzione.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome campo |

### Valore di ritorno

Tabella hash dei valori delle opzioni con chiave in base al nome dell'elemento del modulo

### Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
