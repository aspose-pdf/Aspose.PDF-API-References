---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 텍스트 필드의 정렬 스타일을 설정합니다.
type: docs
weight: 260
url: /ko/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment 메서드

텍스트 필드의 정렬 스타일을 설정합니다.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 자격이 부여된 필드 이름입니다. |
| alignment | Int32 | FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter 및 FormFieldFacade.AlignRight를 포함하는 정렬 스타일 정의입니다. |

### 반환 값

필드를 찾았고 정렬이 설정되면 true입니다.

## 예제

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)