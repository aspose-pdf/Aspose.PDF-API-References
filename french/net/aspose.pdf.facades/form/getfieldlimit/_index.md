---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Obtenez la limitation du champ de texte
type: docs
weight: 230
url: /fr/net/aspose.pdf.facades/form/getfieldlimit/
---
## Méthode Form.GetFieldLimit

Obtenez la limitation du champ de texte.

```csharp
public int GetFieldLimit(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |

### Valeur de retour

Retourne le nombre limite de caractères qu'un champ de texte peut contenir. Si non défini, retourne 0.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)