---
title: "FormEditor.Facade"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية FormEditor. تعيين السمات البصرية للحقل"
type: docs
weight: 40
url: /ar/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

يضبط السمات البصرية للحقل.

```csharp
public FormFieldFacade Facade { get; set; }
```

## أمثلة

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

### انظر أيضًا

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


