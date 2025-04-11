---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Obtiene la limitación del campo de texto
type: docs
weight: 230
url: /es/net/aspose.pdf.facades/form/getfieldlimit/
---
## Método Form.GetFieldLimit

Obtiene la limitación del campo de texto.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo calificado. |

### Valor de Retorno

Devuelve el número de caracteres que se puede llenar en un campo de texto. Si no se establece, devuelve 0.

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)