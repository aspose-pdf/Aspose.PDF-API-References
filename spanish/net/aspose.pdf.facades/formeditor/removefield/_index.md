---
title: RemoveField
second_title: Referencia de API de Aspose.PDF para .NET
description: Eliminar campo del formulario.
type: docs
weight: 250
url: /es/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

Eliminar campo del formulario.

```csharp
public void RemoveField(string fieldName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo que debe ser eliminado. |

### Ejemplos

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Ver también

* class [FormEditor](../../formeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../formeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
