---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: Свойство FormEditor. Член для записи промежутка между двумя соседними радиокнопками в пикселях, по умолчанию 50
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/formeditor/radiogap/
---
## Свойство FormEditor.RadioGap

Член для записи промежутка между двумя соседними радиокнопками в пикселях, по умолчанию 50.

```csharp
public float RadioGap { get; set; }
```

## Примеры

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)