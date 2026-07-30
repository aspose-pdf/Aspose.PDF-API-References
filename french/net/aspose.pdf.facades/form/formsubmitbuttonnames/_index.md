---
title: "Form.FormSubmitButtonNames"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Form. Obtient tous les noms des boutons de soumission du formulaire"
type: docs
weight: 40
url: /fr/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames property

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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


