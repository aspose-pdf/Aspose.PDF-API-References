---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Obtient le nom complet du champ selon son nom de champ court
type: docs
weight: 250
url: /fr/net/aspose.pdf.facades/form/getfullfieldname/
---
## Méthode Form.GetFullFieldName

Obtient le nom complet du champ selon son nom de champ court.

```csharp
public string GetFullFieldName(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ entièrement qualifié. |

### Valeur de retour

Le nom complet du champ.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)