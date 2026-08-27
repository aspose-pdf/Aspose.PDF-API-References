---
title: "FormEditor.DelListItem"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "FormEditor méthode. Supprimer l'élément du champ de liste"
type: docs
weight: 180
url: /fr/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

Supprime l'élément du champ de liste.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ. |
| itemName | String | Nom de l'élément qui doit être supprimé. |

## Exemples

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


