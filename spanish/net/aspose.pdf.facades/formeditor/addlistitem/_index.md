---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Agrega un nuevo elemento a la lista
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Agrega un nuevo elemento a la lista.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo al que se agregará el nuevo elemento. |
| itemName | String | Nombre del nuevo elemento. |

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Agrega un nuevo elemento con valor de Exportación al campo de lista existente, solo para el campo de cuadro combinado de AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo al que se agregarán los elementos. |
| exportName | String[] | Un arreglo de cadenas que denota un nuevo elemento de lista con Valor de Exportación, es decir, (Etiqueta del Elemento, Valor de Exportación). |

## Ejemplos

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)