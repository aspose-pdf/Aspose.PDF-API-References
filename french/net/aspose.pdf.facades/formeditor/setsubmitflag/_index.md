---
title: "FormEditor.SetSubmitFlag"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Définit le drapeau de soumission du bouton de soumission"
type: docs
weight: 330
url: /fr/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

Définit le drapeau de soumission du bouton de soumission.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du bouton de soumission. |
| submitFormFlag | SubmitFormFlag | Drapeau de soumission. |

### Valeur de retour

true si le champ a été trouvé et que le drapeau de soumission a été défini avec succès.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Voir aussi

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


