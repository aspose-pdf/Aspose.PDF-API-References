---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Ottiene il nome completo del campo in base al suo nome breve.
type: docs
weight: 250
url: /it/net/aspose.pdf.facades/form/getfullfieldname/
---
## Metodo Form.GetFullFieldName

Ottiene il nome completo del campo in base al suo nome breve.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo completamente qualificato. |

### Valore di Ritorno

Il nome completo del campo.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)