---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Form method. Returns flags of the field
type: docs
weight: 220
url: /it/net/aspose.pdf.facades/form/getfieldflag/
---
## Metodo Form.GetFieldFlag

Restituisce i flag del campo.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo |

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

### Vedi Anche

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)