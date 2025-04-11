---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Renvoie les indicateurs du champ
type: docs
weight: 220
url: /fr/net/aspose.pdf.facades/form/getfieldflag/
---
## Méthode Form.GetFieldFlag

Renvoie les indicateurs du champ.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ |

### Valeur de retour

Indicateur de propriété (Lecture seule / Requis / Pas d'exportation

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