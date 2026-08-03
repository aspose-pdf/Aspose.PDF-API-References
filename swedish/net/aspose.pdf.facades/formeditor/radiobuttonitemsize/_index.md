---
title: "FormEditor.RadioButtonItemSize"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-egenskap. Hämtar eller anger storleken på radioknappselementet när ett nytt radioknappsfält läggs till"
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## FormEditor.RadioButtonItemSize property

Hämtar eller sätter storlek på radioknappselement (när ett nytt radioknappfält läggs till).

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

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


