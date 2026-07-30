---
title: "FormEditor.AddSubmitBtn"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Ajouter un bouton de soumission au formulaire"
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

Ajoute un bouton d'envoi sur le formulaire.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du nouveau bouton. |
| page | Int32 | Page où le bouton sera placé. |
| étiquette | String | Légende du bouton. |
| url | String | URL du bouton de soumission. |
| llx | Single | Abscisse du coin inférieur gauche. |
| lly | Single | Ordonnée du coin inférieur gauche. |
| urx | Single | Abscisse du coin supérieur droit. |
| ury | Single | Ordonnée du coin supérieur droit. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


