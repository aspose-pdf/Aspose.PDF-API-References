---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Restituisce il tipo di campo
type: docs
weight: 240
url: /it/net/aspose.pdf.facades/form/getfieldtype/
---
## Metodo Form.GetFieldType

Restituisce il tipo di campo.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo. |

### Valore di ritorno

Elemento dell'enumerazione FileType corrispondente al tipo di campo.

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### Vedi Anche

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)