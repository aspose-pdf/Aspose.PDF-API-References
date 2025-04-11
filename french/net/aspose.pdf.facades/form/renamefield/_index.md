---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Renomme un champ. Soit un champ AcroForm soit un champ XFA est acceptable
type: docs
weight: 330
url: /fr/net/aspose.pdf.facades/form/renamefield/
---
## Méthode Form.RenameField

Renomme un champ. Soit un champ AcroForm soit un champ XFA est acceptable.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | l'ancien nom de champ |
| newFieldName | String | le nouveau nom de champ |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)