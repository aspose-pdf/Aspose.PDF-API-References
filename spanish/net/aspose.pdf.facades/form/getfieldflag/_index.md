---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Devuelve las banderas del campo
type: docs
weight: 220
url: /es/net/aspose.pdf.facades/form/getfieldflag/
---
## Método Form.GetFieldFlag

Devuelve las banderas del campo.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo |

### Valor de retorno

Bandera de propiedad (SoloLectura/ Requerido/NoExportar

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### Ver también

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)