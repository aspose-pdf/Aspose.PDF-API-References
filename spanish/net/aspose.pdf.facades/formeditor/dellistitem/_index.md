---
title: DelListItem
second_title: Referencia de API de Aspose.PDF para .NET
description: Eliminar elemento del campo de lista.
type: docs
weight: 220
url: /es/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

Eliminar elemento del campo de lista.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo. |
| itemName | String | Nombre del elemento que debe eliminarse. |

### Ejemplos

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Ver también

* class [FormEditor](../../formeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../formeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->