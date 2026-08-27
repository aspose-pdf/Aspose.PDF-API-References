---
title: "CheckboxField.Value"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété CheckboxField. Obtient ou définit la valeur du champ case à cocher"
type: docs
weight: 70
url: /fr/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value property

Obtient ou définit la valeur du champ case à cocher.

```csharp
public override string Value { get; set; }
```

## Exemples

L'exemple montre comment obtenir et définir la valeur d'une case à cocher à valeurs multiples.

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// Les valeurs autorisées peuvent être récupérées à partir de la collection AllowedStates
// Définissez la valeur de la case à cocher en utilisant la propriété Value
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// La valeur doit être n'importe quel élément de AllowedStates
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Décochez les cases en définissant la Value sur "Off" ou en définissant Checked sur false
checkbox.Value = "Off";
// ou, alternativement :
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### Voir aussi

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


