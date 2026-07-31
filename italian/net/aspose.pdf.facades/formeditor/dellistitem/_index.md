---
title: "FormEditor.DelListItem"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Elimina l'elemento dal campo elenco"
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

Elimina l'elemento dal campo elenco.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo. |
| itemName | String | Nome dell'elemento da eliminare. |

## Esempi

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


