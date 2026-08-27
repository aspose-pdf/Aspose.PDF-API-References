---
title: "FormEditor.Facade"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà FormEditor. Imposta gli attributi visivi del campo"
type: docs
weight: 40
url: /it/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

Imposta gli attributi visivi del campo.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Esempi

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

### Vedi anche

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


