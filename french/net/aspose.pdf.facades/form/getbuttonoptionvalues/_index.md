---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a un sens pour les groupes de boutons radio
type: docs
weight: 190
url: /fr/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Méthode Form.GetButtonOptionValues

Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a un sens pour les groupes de boutons radio.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ |

### Valeur de retour

Table de hachage des valeurs d'option indexées par le nom de l'élément de formulaire

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)