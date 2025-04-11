---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Obtiene el nombre completo del campo según su nombre corto.
type: docs
weight: 250
url: /es/net/aspose.pdf.facades/form/getfullfieldname/
---
## Método Form.GetFullFieldName

Obtiene el nombre completo del campo según su nombre corto.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre de campo completamente calificado. |

### Valor de Retorno

El nombre completo del campo.

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)