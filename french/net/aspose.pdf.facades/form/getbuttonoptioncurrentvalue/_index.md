---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Renvoie la valeur actuelle pour les champs d'option de bouton radio
type: docs
weight: 180
url: /fr/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Méthode Form.GetButtonOptionCurrentValue

Renvoie la valeur actuelle pour les champs d'option de bouton radio.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ |

### Valeur de retour

Valeur de chaîne pour le groupe radio actuel. Voir aussi [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)