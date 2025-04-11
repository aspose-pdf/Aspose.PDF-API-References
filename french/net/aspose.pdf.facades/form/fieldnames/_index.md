---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Propriété Form. Obtient la liste des noms de champs sur le formulaire
type: docs
weight: 30
url: /fr/net/aspose.pdf.facades/form/fieldnames/
---
## Propriété Form.FieldNames

Obtient la liste des noms de champs sur le formulaire.

```csharp
public string[] FieldNames { get; }
```

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)