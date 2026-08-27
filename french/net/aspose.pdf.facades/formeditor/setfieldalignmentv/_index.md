---
title: "FormEditor.SetFieldAlignmentV"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Définir le style d'alignement vertical d'un champ texte"
type: docs
weight: 270
url: /fr/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

Définit le style d'alignement vertical d'un champ texte.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |
| alignment | Int32 | La définition du style d'alignement, incluant FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle et FormFieldFacade.AlignRight. |

### Valeur de retour

true si le champ a été trouvé et que l'alignement a été appliqué avec succès.

## Exemples

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


