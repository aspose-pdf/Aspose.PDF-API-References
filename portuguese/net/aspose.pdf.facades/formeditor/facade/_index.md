---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: Propriedade FormEditor. Define atributos visuais do campo
type: docs
weight: 40
url: /pt/net/aspose.pdf.facades/formeditor/facade/
---
## Propriedade FormEditor.Facade

Define atributos visuais do campo.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Exemplos

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

### Veja Também

* classe [FormFieldFacade](../../formfieldfacade/)
* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)