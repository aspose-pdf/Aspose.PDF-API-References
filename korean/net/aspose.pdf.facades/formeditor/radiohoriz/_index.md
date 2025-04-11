---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 속성. 라디오 버튼이 수평 또는 수직으로 배열되는지를 나타내는 플래그, 기본값은 true
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz 속성

라디오 버튼이 수평 또는 수직으로 배열되는지를 나타내는 플래그, 기본값은 true입니다.

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

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)