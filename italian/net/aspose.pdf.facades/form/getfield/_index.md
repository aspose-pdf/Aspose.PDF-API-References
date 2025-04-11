---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Ottiene il valore del campo in base al nome del campo
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/form/getfield/
---
## Metodo Form.GetField

Ottiene il valore del campo in base al nome del campo.

```csharp
public string GetField(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo completamente qualificato. |

### Valore di Ritorno

Il valore del campo.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)