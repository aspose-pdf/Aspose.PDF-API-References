---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Change un champ de texte à une seule ligne en un champ à plusieurs lignes
type: docs
weight: 350
url: /fr/net/aspose.pdf.facades/formeditor/single2multiple/
---
## Méthode FormEditor.Single2Multiple

Change un champ de texte à une seule ligne en un champ à plusieurs lignes.

```csharp
public bool Single2Multiple(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |

### Valeur de retour

En cas de succès, retourne true ; sinon false.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)