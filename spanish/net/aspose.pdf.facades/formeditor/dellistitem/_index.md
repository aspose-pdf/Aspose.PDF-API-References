---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Eliminar elemento del campo de lista
type: docs
weight: 180
url: /es/net/aspose.pdf.facades/formeditor/dellistitem/
---
## Método FormEditor.DelListItem

Eliminar elemento del campo de lista.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo. |
| itemName | String | Nombre del elemento que debe ser eliminado. |

## Ejemplos

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)