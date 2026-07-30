---
title: "FormEditor.RemoveFieldAction"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "FormEditor méthode. Supprimer l'action de soumission du champ"
type: docs
weight: 220
url: /fr/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction method

Supprime l'action de soumission du champ.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


