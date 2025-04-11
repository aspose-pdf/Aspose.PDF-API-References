---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Supprimer un champ du formulaire
type: docs
weight: 210
url: /fr/net/aspose.pdf.facades/formeditor/removefield/
---
## Méthode FormEditor.RemoveField

Supprimer un champ du formulaire.

```csharp
public void RemoveField(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ qui doit être supprimé. |

## Exemples

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)