---
title: "FormEditor.Facade"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-egenskap. Anger visuella attribut för fältet"
type: docs
weight: 40
url: /sv/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

Ställer in visuella attribut för fältet.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Exempel

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

### Se även

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


