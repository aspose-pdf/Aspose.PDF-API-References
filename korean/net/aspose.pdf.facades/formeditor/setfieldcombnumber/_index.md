---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. combNumber 매개변수의 값만큼 필드가 자동으로 동일하게 간격을 두고 나누어지는 일반 단일 행 텍스트 필드의 comb 수를 설정합니다.
type: docs
weight: 300
url: /ko/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber 메서드

combNumber 매개변수의 값만큼 필드가 자동으로 동일하게 간격을 두고 나누어지는 일반 단일 행 텍스트 필드의 comb 수를 설정합니다.

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 자격이 부여된 필드 이름. |
| combNumber | Int32 | 필드를 나누는 comb의 수. |

### 반환 값

성공하면 true를 반환하고, 그렇지 않으면 false를 반환합니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)