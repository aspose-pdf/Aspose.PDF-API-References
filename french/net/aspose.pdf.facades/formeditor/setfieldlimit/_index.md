---
title: "FormEditor.SetFieldLimit"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Définit le nombre maximal de caractères du champ texte"
type: docs
weight: 310
url: /fr/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

Définit le nombre maximal de caractères du champ texte.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ texte. |
| fieldLimit | Int32 | Nouvelle valeur de la limite pour le champ. |

### Valeur de retour

true si la limite du champ a été définie avec succès.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


