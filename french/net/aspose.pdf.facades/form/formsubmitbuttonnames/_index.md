---
title: FormSubmitButtonNames
second_title: Référence de l'API Aspose.PDF pour .NET
description: Obtient tous les noms de bouton de soumission de formulaire.
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames property

Obtient tous les noms de bouton de soumission de formulaire.

```csharp
public string[] FormSubmitButtonNames { get; }
```

### Exemples

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Voir également

* class [Form](../../form)
* espace de noms [Aspose.Pdf.Facades](../../form)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
