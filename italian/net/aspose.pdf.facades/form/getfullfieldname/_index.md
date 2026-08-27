---
title: "Form.GetFullFieldName"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Ottiene il nome completo del campo in base al suo nome breve."
type: docs
weight: 250
url: /it/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

Ottiene il nome campo completo in base al suo nome campo breve.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome completo del campo. |

### Valore di ritorno

Il nome completo del campo.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


