---
title: "Form.GetFieldLimit"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Obtient la limitation du champ texte"
type: docs
weight: 230
url: /fr/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

Obtient la limitation du champ texte.

```csharp
public int GetFieldLimit(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |

### Valeur de retour

Retourne le nombre maximal de caractères qu'un champ texte peut contenir. S'il n'est pas défini, retourne 0.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


