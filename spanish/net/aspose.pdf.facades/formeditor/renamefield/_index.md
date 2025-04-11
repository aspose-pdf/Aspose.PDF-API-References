---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Cambiar el nombre del campo
type: docs
weight: 230
url: /es/net/aspose.pdf.facades/formeditor/renamefield/
---
## Método FormEditor.RenameField

Cambiar el nombre del campo.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre antiguo del campo. |
| newFieldName | String | Nuevo nombre del campo. |

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)