---
title: "Form.FlattenField"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Appiattisce un campo specificato con il nome completo del campo. Qualsiasi altro campo rimarrà invariato. Se il fieldName non è valido tutti i campi rimarranno invariati."
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

Appiattisce un campo specificato con il nome campo completamente qualificato. Qualsiasi altro campo rimarrà invariato. Se il fieldName è non valido, tutti i campi rimarranno invariati.

```csharp
public void FlattenField(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo da appiattire. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


