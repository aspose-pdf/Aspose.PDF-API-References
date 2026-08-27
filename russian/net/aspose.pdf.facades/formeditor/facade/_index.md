---
title: "FormEditor.Facade"
second_title: "Справочник API Aspose.PDF для .NET"
description: "свойство FormEditor. Устанавливает визуальные атрибуты поля"
type: docs
weight: 40
url: /ru/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

Устанавливает визуальные атрибуты поля.

```csharp
public FormFieldFacade Facade { get; set; }
```

## Примеры

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

### См. также

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


