---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Définir la nouvelle position du champ
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/formeditor/movefield/
---
## Méthode FormEditor.MoveField

Définir la nouvelle position du champ.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ qui doit être déplacé. |
| llx | Single | Abscisse du coin inférieur gauche du champ. |
| lly | Single | Ordonnée du coin inférieur gauche du champ. |
| urx | Single | Abscisse du coin supérieur droit du champ. |
| ury | Single | Ordonnée du coin supérieur droit du champ. |

### Valeur de retour

true si la position du champ a été changée avec succès.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)