---
title: GetFieldFlag
second_title: Référence de l'API Aspose.PDF pour .NET
description: Renvoie les drapeaux du champ.
type: docs
weight: 250
url: /fr/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag method

Renvoie les drapeaux du champ.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom de domaine |

### Return_Value

Indicateur de propriété (ReadOnly/Required/NoExport

### Exemples

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### Voir également

* enum [PropertyFlag](../../propertyflag)
* class [Form](../../form)
* espace de noms [Aspose.Pdf.Facades](../../form)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->