---
title: "Form.FieldNames"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Form. Obtient la liste des noms de champs du formulaire."
type: docs
weight: 30
url: /fr/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames property

Obtient la liste des noms de champs du formulaire.

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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


