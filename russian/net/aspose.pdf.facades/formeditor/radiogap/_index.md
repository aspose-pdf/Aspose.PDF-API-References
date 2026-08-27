---
title: "FormEditor.RadioGap"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство FormEditor. Член, фиксирующий промежуток между двумя соседними радиокнопками в пикселях, по умолчанию 50"
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap property

Член, фиксирующий промежуток между двумя соседними радиокнопками в пикселях, по умолчанию 50.

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


