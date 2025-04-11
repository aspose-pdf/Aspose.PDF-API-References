---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Form method. Returns the current value for radio button option fields
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Metodo Form.GetButtonOptionCurrentValue

Restituisce il valore attuale per i campi delle opzioni dei pulsanti radio.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo |

### Valore di ritorno

Valore stringa per l'attuale gruppo di opzioni radio. Vedi anche [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Vedi anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)