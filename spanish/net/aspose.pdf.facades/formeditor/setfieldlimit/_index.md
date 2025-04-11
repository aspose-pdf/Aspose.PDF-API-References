---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Establece el recuento máximo de caracteres del campo de texto
type: docs
weight: 310
url: /es/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## Método FormEditor.SetFieldLimit

Establece el recuento máximo de caracteres del campo de texto.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo de texto. |
| fieldLimit | Int32 | Nuevo valor del límite para el campo. |

### Valor de Retorno

true si el límite del campo se estableció correctamente.

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)