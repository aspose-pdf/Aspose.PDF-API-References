---
title: GetButtonOptionCurrentValue
second_title: Référence de l'API Aspose.PDF pour .NET
description: Renvoie la valeur actuelle des champs doption de bouton radio.
type: docs
weight: 210
url: /fr/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue method

Renvoie la valeur actuelle des champs d'option de bouton radio.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom de domaine |

### Return_Value

Valeur de chaîne pour l'optino du groupe radio actuel. Voir également[`GetButtonOptionValues`](../getbuttonoptionvalues)

### Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Voir également

* class [Form](../../form)
* espace de noms [Aspose.Pdf.Facades](../../form)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
