---
title: GetFieldFacade
second_title: Referencia de API de Aspose.PDF para .NET
description: Devuelve el objeto FrofmFieldFacade que contiene todos los atributos de apariencia.
type: docs
weight: 240
url: /es/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

Devuelve el objeto FrofmFieldFacade que contiene todos los atributos de apariencia.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo a leer. |

### Valor_devuelto

Objeto FormFieldFacade

### Ver también

* class [FormFieldFacade](../../formfieldfacade)
* class [Form](../../form)
* espacio de nombres [Aspose.Pdf.Facades](../../form)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
