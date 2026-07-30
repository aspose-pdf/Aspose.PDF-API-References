---
title: "Form.GetFullFieldName"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Obtient le nom complet du champ selon son nom court"
type: docs
weight: 250
url: /fr/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

Obtient le nom complet du champ selon son nom court.

```csharp
public string GetFullFieldName(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom complet du champ. |

### Valeur de retour

Le nom complet du champ.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


