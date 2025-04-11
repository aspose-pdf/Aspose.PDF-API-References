---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Eliminar campo del formulario
type: docs
weight: 210
url: /es/net/aspose.pdf.facades/formeditor/removefield/
---
## Método FormEditor.RemoveField

Eliminar campo del formulario.

```csharp
public void RemoveField(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo que debe ser eliminado. |

## Ejemplos

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)