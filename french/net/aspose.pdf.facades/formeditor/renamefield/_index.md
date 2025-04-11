---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Changer le nom du champ
type: docs
weight: 230
url: /fr/net/aspose.pdf.facades/formeditor/renamefield/
---
## Méthode FormEditor.RenameField

Changer le nom du champ.

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

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)