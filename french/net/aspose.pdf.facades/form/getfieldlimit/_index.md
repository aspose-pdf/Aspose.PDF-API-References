---
title: GetFieldLimit
second_title: Référence de l'API Aspose.PDF pour .NET
description: Obtenez la limitation du champ de texte.
type: docs
weight: 260
url: /fr/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

Obtenez la limitation du champ de texte.

```csharp
public int GetFieldLimit(string fieldName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom de champ qualifié. |

### Return_Value

Renvoie le nombre limite de caractères qu'un champ de texte peut contenir. Il n'est pas défini, renvoie 0.

### Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Voir également

* class [Form](../../form)
* espace de noms [Aspose.Pdf.Facades](../../form)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->