---
title: "FormEditor.RadioButtonItemSize"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor property. 새 라디오 버튼 필드가 추가될 때 라디오 버튼 항목 크기를 가져오거나 설정합니다."
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## FormEditor.RadioButtonItemSize property

새 라디오 버튼 필드가 추가될 때 라디오 버튼 항목 크기를 가져오거나 설정합니다.

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

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


