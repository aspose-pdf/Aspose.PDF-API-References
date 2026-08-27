---
title: "Form.GetFieldType"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Restituisce il tipo del campo"
type: docs
weight: 240
url: /it/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType method

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

### Vedi anche

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


