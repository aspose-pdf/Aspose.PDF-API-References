---
title: "FormEditor.SetFieldAlignment"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Définit le style d'alignement d'un champ texte"
type: docs
weight: 260
url: /fr/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

Définit le style d'alignement d'un champ texte.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |
| alignment | Int32 | La définition du style d'alignement, incluant FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter et FormFieldFacade.AlignRight. |

### Valeur de retour

true si le champ a été trouvé et que l'alignement a été défini.

## Exemples

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


