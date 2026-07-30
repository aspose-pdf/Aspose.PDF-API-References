---
title: "FormEditor.RemoveField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Supprime le champ du formulaire."
type: docs
weight: 210
url: /fr/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

Supprime le champ du formulaire.

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


