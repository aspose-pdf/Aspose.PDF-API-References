---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Devuelve el valor actual para los campos de opción de botón de radio
type: docs
weight: 180
url: /es/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Método Form.GetButtonOptionCurrentValue

Devuelve el valor actual para los campos de opción de botón de radio.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo |

### Valor de retorno

Valor de cadena para la opción actual del grupo de botones de radio. Ver también [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Ver también

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)