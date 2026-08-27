---
title: "FormEditor.SetFieldCombNumber"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Définit le nombre de créneaux pour un champ texte à ligne unique standard ; le champ est automatiquement divisé en autant de positions ou créneaux également espacés que la valeur du paramètre combNumber"
type: docs
weight: 300
url: /fr/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

Définit le nombre de créneaux pour un champ texte à ligne unique standard (le champ est automatiquement divisé en autant de positions également espacées, ou créneaux, que la valeur du paramètre combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |
| combNumber | Int32 | Le nombre de créneaux pour diviser le champ. |

### Valeur de retour

Si succès, renvoie true ; sinon false.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


