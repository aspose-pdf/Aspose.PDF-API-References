---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Elimina un elemento dal campo elenco
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/formeditor/dellistitem/
---
## Metodo FormEditor.DelListItem

Elimina un elemento dal campo elenco.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo. |
| itemName | String | Nome dell'elemento che deve essere eliminato. |

## Esempi

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Vedi anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)