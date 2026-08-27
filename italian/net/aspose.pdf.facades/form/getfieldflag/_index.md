---
title: "Form.GetFieldFlag"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Restituisce i flag del campo"
type: docs
weight: 220
url: /it/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag method

Restituisce i flag del campo.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome campo |

### Valore di ritorno

Flag della proprietà (ReadOnly/ Required/NoExport

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### Vedi anche

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


