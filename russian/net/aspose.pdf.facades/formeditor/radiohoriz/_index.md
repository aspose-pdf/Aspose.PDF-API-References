---
title: RadioHoriz
second_title: Aspose.PDF для справочника API .NET
description: Флаг указывающий расположены ли радиостанции горизонтально или вертикально значение по умолчанию  true.
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

Флаг, указывающий, расположены ли радиостанции горизонтально или вертикально, значение по умолчанию — true.

```csharp
public bool RadioHoriz { get; set; }
```

### Примеры

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Смотрите также

* class [FormEditor](../../formeditor)
* пространство имен [Aspose.Pdf.Facades](../../formeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->