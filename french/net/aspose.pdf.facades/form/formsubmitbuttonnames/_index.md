---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Propriété du formulaire. Obtient tous les noms des boutons de soumission du formulaire
type: docs
weight: 40
url: /fr/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Propriété Form.FormSubmitButtonNames

Obtient tous les noms des boutons de soumission du formulaire.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)