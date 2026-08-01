---
title: "FormEditor.SetFieldAlignmentV"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 텍스트 필드의 수직 정렬 스타일을 설정합니다."
type: docs
weight: 270
url: /ko/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

텍스트 필드의 수직 정렬 스타일을 설정합니다.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 정규화된 필드 이름입니다. |
| 정렬 | Int32 | 정렬 스타일 정의이며, FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle 및 FormFieldFacade.AlignRight를 포함합니다. |

### 반환 값

필드를 찾았고 정렬이 성공적으로 적용된 경우 true.

## 예제

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


