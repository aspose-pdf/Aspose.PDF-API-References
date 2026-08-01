---
title: "FormEditor.RadioHoriz"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 속성. 라디오가 가로로 배열되는지 세로로 배열되는지를 나타내는 플래그이며 기본값은 true입니다."
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

라디오 버튼이 가로로 배열되는지 세로로 배열되는지를 나타내는 플래그이며, 기본값은 true입니다.

```csharp
public bool RadioHoriz { get; set; }
```

## 예제

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


