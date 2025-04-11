---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: FormEditor özelliği. Alanın görsel niteliklerini ayarlar
type: docs
weight: 40
url: /tr/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade özelliği

Alanın görsel niteliklerini ayarlar.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Örnekler

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

### Ayrıca Bakınız

* sınıf [FormFieldFacade](../../formfieldfacade/)
* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)