---
title: "Form.GetFieldFlag"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Retourne les indicateurs du champ"
type: docs
weight: 220
url: /fr/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag method

Renvoie les indicateurs du champ.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ |

### Valeur de retour

Indicateur de propriété (ReadOnly/ Required/NoExport

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### Voir aussi

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


