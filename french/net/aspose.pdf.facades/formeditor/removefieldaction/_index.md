---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Supprimer l'action de soumission du champ
type: docs
weight: 220
url: /fr/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## Méthode FormEditor.RemoveFieldAction

Supprimer l'action de soumission du champ.

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

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)