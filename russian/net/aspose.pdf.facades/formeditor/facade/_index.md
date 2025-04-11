---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: Свойство FormEditor. Устанавливает визуальные атрибуты поля
type: docs
weight: 40
url: /ru/net/aspose.pdf.facades/formeditor/facade/
---
## Свойство FormEditor.Facade

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

* класс [FormFieldFacade](../../formfieldfacade/)
* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)