---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Establecer atributos de campo
type: docs
weight: 290
url: /es/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## Método FormEditor.SetFieldAttribute

Establecer atributos de campo.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo cuyos atributos deben ser establecidos. |
| flag | PropertyFlag | Bandera (NoExport/ReadOnly/Required) |

### Valor de Retorno

true si el atributo se estableció correctamente.

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Ver También

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)