---
title: "Form.GetButtonOptionValues"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Obtient les champs d'options de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a une signification pour les groupes de boutons radio"
type: docs
weight: 190
url: /fr/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a une utilité pour les groupes de boutons radio.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ |

### Valeur de retour

Table de hachage des valeurs d'option indexées par le nom de l'élément du formulaire

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


