---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Eigenschaft. Setzt visuelle Attribute des Feldes
type: docs
weight: 40
url: /de/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade-Eigenschaft

Setzt visuelle Attribute des Feldes.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Beispiele

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

### Siehe auch

* Klasse [FormFieldFacade](../../formfieldfacade/)
* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)