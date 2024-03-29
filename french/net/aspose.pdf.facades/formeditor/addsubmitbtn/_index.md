---
title: AddSubmitBtn
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ajouter un bouton denvoi sur le formulaire.
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

Ajouter un bouton d'envoi sur le formulaire.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom du nouveau bouton. |
| page | Int32 | Page où le bouton sera placé. |
| label | String | Légende du bouton. |
| url | String | URL du bouton d'envoi. |
| llx | Single | Abscisse du coin inférieur gauche. |
| lly | Single | Ordonnée du coin inférieur gauche. |
| urx | Single | Abscisse du coin supérieur droit. |
| ury | Single | Ordonnée du coin supérieur droit. |

### Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Voir également

* class [FormEditor](../../formeditor)
* espace de noms [Aspose.Pdf.Facades](../../formeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
