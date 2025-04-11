---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Obtenez la valeur d'un champ de texte enrichi, y compris les informations de formatage de chaque caractère
type: docs
weight: 260
url: /fr/net/aspose.pdf.facades/form/getrichtext/
---
## Méthode Form.GetRichText

Obtenez la valeur d'un champ de texte enrichi, y compris les informations de formatage de chaque caractère.

```csharp
public string GetRichText(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ entièrement qualifié du champ de texte enrichi. |

### Valeur de retour

Retourne une chaîne contenant des informations de formatage du champ de texte enrichi.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)