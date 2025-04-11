---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. Este método tiene significado para grupos de botones de radio.
type: docs
weight: 190
url: /es/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Método Form.GetButtonOptionValues

Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. Este método tiene significado para grupos de botones de radio.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo |

### Valor de retorno

Tabla hash de valores de opción indexados por el nombre del elemento del formulario

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Ver también

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)