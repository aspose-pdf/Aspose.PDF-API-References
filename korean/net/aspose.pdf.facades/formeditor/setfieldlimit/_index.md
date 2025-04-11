---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 텍스트 필드의 최대 문자 수를 설정합니다.
type: docs
weight: 310
url: /ko/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit 메서드

텍스트 필드의 최대 문자 수를 설정합니다.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 텍스트 필드의 이름. |
| fieldLimit | Int32 | 필드의 새로운 제한 값. |

### 반환 값

필드 제한이 성공적으로 설정되면 true입니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)