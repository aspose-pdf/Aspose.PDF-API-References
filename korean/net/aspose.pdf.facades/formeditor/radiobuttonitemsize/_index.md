---
title: FormEditor.RadioButtonItemSize
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 속성. 새 라디오 버튼 필드가 추가될 때 라디오 버튼 항목 크기를 가져오거나 설정합니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## FormEditor.RadioButtonItemSize 속성

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

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)