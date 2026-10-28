---
title: "FormEditor.SetFieldCombNumber"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 일반 단일 행 텍스트 필드에 대한 콤(칸) 수를 설정합니다. 필드는 combNumber 매개변수 값만큼 동일한 간격의 위치 또는 콤으로 자동 분할됩니다."
type: docs
weight: 300
url: /ko/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

일반 단일 행 텍스트 필드의 콤 수를 설정합니다(필드는 combNumber 매개변수 값만큼 동일한 간격의 위치, 즉 콤으로 자동 분할됩니다).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 정규화된 필드 이름입니다. |
| combNumber | Int32 | 필드를 분할할 콤(칸)의 수입니다. |

### 반환 값

성공하면 true를 반환하고, 그렇지 않으면 false를 반환합니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


