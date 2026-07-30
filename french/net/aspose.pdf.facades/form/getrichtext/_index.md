---
title: "Form.GetRichText"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Obtient la valeur d'un champ Rich Text incluant les informations de formatage de chaque caractère"
type: docs
weight: 260
url: /fr/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

Obtient la valeur d'un champ de texte enrichi, incluant les informations de formatage de chaque caractère.

```csharp
public string GetRichText(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom complet du champ Rich Text. |

### Valeur de retour

Renvoie une chaîne contenant les informations de formatage du champ Rich Text.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


