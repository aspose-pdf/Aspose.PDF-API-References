---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Obtiene el valor del campo según su nombre de campo
type: docs
weight: 200
url: /es/net/aspose.pdf.facades/form/getfield/
---
## Método Form.GetField

Obtiene el valor del campo según su nombre de campo.

```csharp
public string GetField(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre de campo completamente calificado. |

### Valor de Retorno

El valor del campo.

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)