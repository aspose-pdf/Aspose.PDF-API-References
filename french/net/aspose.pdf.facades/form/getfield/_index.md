---
title: "Form.GetField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Obtient la valeur du champ selon son nom."
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

Obtient la valeur du champ selon son nom de champ.

```csharp
public string GetField(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom complet du champ. |

### Valeur de retour

Valeur du champ.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


