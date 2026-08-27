---
title: "Form.GetButtonOptionCurrentValue"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Restituisce il valore corrente per i campi di opzione dei pulsanti radio"
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue method

Restituisce il valore corrente per i campi opzione dei pulsanti radio.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome Campo |

### Valore di ritorno

Valore stringa per l'opzione corrente del gruppo radio. Vedi anche [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


