---
title: SetFieldCombNumber
second_title: Référence de l'API Aspose.PDF pour .NET
description: Définit le nombre de peignes pour un champ de texte régulier sur une seule ligne le champ est automatiquement divisé en autant de positions équidistantes ou peignes que la valeur du paramètre combNumber.
type: docs
weight: 340
url: /fr/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

Définit le nombre de peignes pour un champ de texte régulier sur une seule ligne (le champ est automatiquement divisé en autant de positions équidistantes, ou peignes, que la valeur du paramètre combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom de champ qualifié. |
| combNumber | Int32 | Le nombre de peignes dans lesquels diviser le champ. |

### Return_Value

En cas de succès, renvoie vrai ; sinon faux.

### Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Voir également

* class [FormEditor](../../formeditor)
* espace de noms [Aspose.Pdf.Facades](../../formeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->