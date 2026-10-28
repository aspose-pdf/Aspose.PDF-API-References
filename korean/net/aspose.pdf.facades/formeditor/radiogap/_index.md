---
title: "FormEditor.RadioGap"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 속성. 두 인접 라디오 버튼 사이의 간격을 픽셀 단위로 기록하는 멤버이며 기본값은 50입니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap property

두 개의 인접한 라디오 버튼 사이의 간격을 픽셀 단위로 기록하는 멤버이며, 기본값은 50입니다.

```csharp
public float RadioGap { get; set; }
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


