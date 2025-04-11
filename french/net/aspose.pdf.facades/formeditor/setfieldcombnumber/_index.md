---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Définit le nombre de peignes pour un champ de texte simple régulier, le champ étant automatiquement divisé en autant de positions ou peignes également espacés que la valeur du paramètre combNumber.
type: docs
weight: 300
url: /fr/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## Méthode FormEditor.SetFieldCombNumber

Définit le nombre de peignes pour un champ de texte simple (le champ est automatiquement divisé en autant de positions également espacées, ou peignes, que la valeur du paramètre combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |
| combNumber | Int32 | Le nombre de peignes pour diviser le champ. |

### Valeur de retour

En cas de succès, retourne true ; sinon false.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)