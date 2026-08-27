---
title: "FormEditor.Facade"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "FormEditor property. Menetapkan atribut visual field"
type: docs
weight: 40
url: /id/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

Mengatur atribut visual bidang.

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

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


