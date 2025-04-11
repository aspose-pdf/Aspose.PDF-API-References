---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Devuelve un objeto FrofmFieldFacade que contiene todos los atributos de apariencia
type: docs
weight: 210
url: /es/net/aspose.pdf.facades/form/getfieldfacade/
---
## Método Form.GetFieldFacade

Devuelve un objeto FrofmFieldFacade que contiene todos los atributos de apariencia.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo a leer. |

### Valor de retorno

Objeto FormFieldFacade

### Véase también

* clase [FormFieldFacade](../../formfieldfacade/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)