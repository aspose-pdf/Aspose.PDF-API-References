---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Eliminar acción de envío del campo
type: docs
weight: 220
url: /es/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## Método FormEditor.RemoveFieldAction

Eliminar acción de envío del campo.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo. |

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)