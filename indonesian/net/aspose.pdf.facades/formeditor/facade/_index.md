---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: Properti FormEditor. Mengatur atribut visual dari field
type: docs
weight: 40
url: /id/net/aspose.pdf.facades/formeditor/facade/
---
## Properti FormEditor.Facade

Mengatur atribut visual dari field.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Contoh

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

### Lihat Juga

* kelas [FormFieldFacade](../../formfieldfacade/)
* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)