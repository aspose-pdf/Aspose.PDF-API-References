---
title: FormEditor.RadioButtonItemSize
second_title: Aspose.PDF for .NET API Reference
description: Свойство FormEditor. Получает или устанавливает размер элемента радиокнопки при добавлении нового поля радиокнопки
type: docs
weight: 60
url: /ru/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## Свойство FormEditor.RadioButtonItemSize

Получает или устанавливает размер элемента радиокнопки (при добавлении нового поля радиокнопки).

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.RadioButtonItemSize = 20;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public double RadioButtonItemSize { get; set; }
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)