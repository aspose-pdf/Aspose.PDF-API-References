---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Devuelve el tipo de campo
type: docs
weight: 240
url: /es/net/aspose.pdf.facades/form/getfieldtype/
---
## Método Form.GetFieldType

Devuelve el tipo de campo.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo. |

### Valor de Retorno

Elemento de la enumeración FileType correspondiente al tipo de campo.

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### Ver También

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)