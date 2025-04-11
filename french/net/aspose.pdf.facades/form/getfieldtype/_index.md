---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Renvoie le type de champ
type: docs
weight: 240
url: /fr/net/aspose.pdf.facades/form/getfieldtype/
---
## Méthode Form.GetFieldType

Renvoie le type de champ.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ. |

### Valeur de retour

Élément de l'énumération FileType correspondant au type de champ.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### Voir aussi

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)