---
title: "Form.RenameField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Renomme un champ. Un champ AcroForm ou XFA est acceptable."
type: docs
weight: 330
url: /fr/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

Renomme un champ. Un champ AcroForm ou XFA convient.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | l'ancien nom du champ |
| newFieldName | String | le nouveau nom du champ |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


