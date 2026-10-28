---
title: "FormEditor.SetFieldLimit"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 텍스트 필드의 최대 문자 수를 설정합니다."
type: docs
weight: 310
url: /ko/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

텍스트 필드의 최대 문자 수를 설정합니다.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 텍스트 필드의 이름입니다. |
| fieldLimit | Int32 | 필드 제한의 새 값입니다. |

### 반환 값

필드 제한이 성공적으로 설정된 경우 true입니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


