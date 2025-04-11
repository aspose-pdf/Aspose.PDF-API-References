---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Définir le style d'alignement vertical d'un champ de texte
type: docs
weight: 270
url: /fr/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## Méthode FormEditor.SetFieldAlignmentV

Définir le style d'alignement vertical d'un champ de texte.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |
| alignment | Int32 | La définition du style d'alignement, y compris FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle et FormFieldFacade.AlignRight. |

### Valeur de retour

true si le champ a été trouvé et que l'alignement a été rempli avec succès.

## Exemples

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)