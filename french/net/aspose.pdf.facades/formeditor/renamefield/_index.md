---
title: "FormEditor.RenameField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Modifie le nom du champ."
type: docs
weight: 230
url: /fr/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

Modifie le nom du champ.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Ancien nom du champ. |
| newFieldName | String | Nouveau nom du champ. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


