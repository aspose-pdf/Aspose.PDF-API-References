---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Obtient la valeur des champs selon son nom de champ
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/form/getfield/
---
## Méthode Form.GetField

Obtient la valeur du champ selon son nom de champ.

```csharp
public string GetField(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ entièrement qualifié. |

### Valeur de retour

La valeur du champ.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)