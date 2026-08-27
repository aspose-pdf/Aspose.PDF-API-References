---
title: "Form.GetButtonOptionCurrentValue"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Retourne la valeur actuelle des champs d'options de bouton radio"
type: docs
weight: 180
url: /fr/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue method

Renvoie la valeur actuelle des champs d'option de bouton radio.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ |

### Valeur de retour

Valeur chaîne pour l'optino du groupe radio actuel. Voir aussi [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


