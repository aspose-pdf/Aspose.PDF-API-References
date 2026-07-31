---
title: "Form.GetField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Ottiene il valore del campo in base al nome del campo"
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

Ottiene il valore del campo in base al suo nome.

```csharp
public string GetField(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome completo del campo. |

### Valore di ritorno

Il valore del campo.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


