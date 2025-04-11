---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: Propriété FormEditor. Définit les attributs visuels du champ
type: docs
weight: 40
url: /fr/net/aspose.pdf.facades/formeditor/facade/
---
## Propriété FormEditor.Facade

Définit les attributs visuels du champ.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Exemples

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
fe.Save();
```

### Voir aussi

* classe [FormFieldFacade](../../formfieldfacade/)
* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)