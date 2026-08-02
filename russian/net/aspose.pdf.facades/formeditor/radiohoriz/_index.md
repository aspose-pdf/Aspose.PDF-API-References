---
title: "FormEditor.RadioHoriz"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство FormEditor. Флаг, указывающий, размещаются ли переключатели горизонтально или вертикально; значение по умолчанию — true"
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

Флаг, указывающий, расположены ли радиокнопки горизонтально или вертикально, значение по умолчанию — true.

```csharp
public bool RadioHoriz { get; set; }
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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


