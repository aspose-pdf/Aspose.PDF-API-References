---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 텍스트 필드의 수직 정렬 스타일을 설정합니다.
type: docs
weight: 270
url: /ko/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV 메서드

텍스트 필드의 수직 정렬 스타일을 설정합니다.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 자격이 부여된 필드 이름입니다. |
| alignment | Int32 | FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle 및 FormFieldFacade.AlignRight를 포함하는 정렬 스타일 정의입니다. |

### 반환 값

필드를 찾았고 정렬이 성공적으로 채워지면 true입니다.

## 예제

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)