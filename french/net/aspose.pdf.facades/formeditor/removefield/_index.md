---
title: RemoveField
second_title: Référence de l'API Aspose.PDF pour .NET
description: Supprimer le champ du formulaire.
type: docs
weight: 250
url: /fr/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

Supprimer le champ du formulaire.

```csharp
public void RemoveField(string fieldName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom du champ qui doit être supprimé. |

### Exemples

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Voir également

* class [FormEditor](../../formeditor)
* espace de noms [Aspose.Pdf.Facades](../../formeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
