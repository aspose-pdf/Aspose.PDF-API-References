---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Définit le nombre maximum de caractères du champ de texte
type: docs
weight: 310
url: /fr/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## Méthode FormEditor.SetFieldLimit

Définit le nombre maximum de caractères du champ de texte.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ de texte. |
| fieldLimit | Int32 | Nouvelle valeur de limite pour le champ. |

### Valeur de retour

true si la limite du champ a été définie avec succès.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)