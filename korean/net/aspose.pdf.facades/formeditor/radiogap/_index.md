---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 속성. 두 인접한 라디오 버튼 사이의 간격을 픽셀 단위로 기록하는 멤버, 기본값은 50
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap 속성

두 인접한 라디오 버튼 사이의 간격을 픽셀 단위로 기록하는 멤버, 기본값은 50입니다.

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

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)