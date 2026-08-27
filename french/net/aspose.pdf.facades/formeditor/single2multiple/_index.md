---
title: "FormEditor.Single2Multiple"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "FormEditor méthode. Modifier un champ texte à ligne unique en un champ à plusieurs lignes"
type: docs
weight: 350
url: /fr/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

Convertit un champ texte à ligne unique en un champ texte à plusieurs lignes.

```csharp
public bool Single2Multiple(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |

### Valeur de retour

Si succès, renvoie true ; sinon false.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


