---
title: "FormEditor.SetFieldAttribute"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Définit les attributs du champ"
type: docs
weight: 290
url: /fr/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute method

Définit les attributs du champ.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ dont les attributs doivent être définis. |
| flag | PropertyFlag | Drapeau (NoExport/ReadOnly/Required) |

### Valeur de retour

true si l'attribut a été défini avec succès.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Voir aussi

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


