---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Obtiene el valor de un campo de Rich Text incluyendo la información de formato de cada carácter
type: docs
weight: 260
url: /es/net/aspose.pdf.facades/form/getrichtext/
---
## Método Form.GetRichText

Obtiene el valor de un campo de Rich Text, incluyendo la información de formato de cada carácter.

```csharp
public string GetRichText(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre de campo completamente calificado del campo de Rich Text. |

### Valor de Retorno

Devuelve una cadena que contiene la información de formato del campo de Rich Text.

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Véase También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)