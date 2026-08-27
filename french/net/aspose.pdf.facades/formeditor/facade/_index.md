---
title: "FormEditor.Facade"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "FormEditor propriété. Définit les attributs visuels du champ"
type: docs
weight: 40
url: /fr/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

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

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


