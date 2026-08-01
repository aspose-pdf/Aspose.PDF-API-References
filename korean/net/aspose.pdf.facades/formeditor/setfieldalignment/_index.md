---
title: "FormEditor.SetFieldAlignment"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 텍스트 필드의 정렬 스타일을 설정합니다."
type: docs
weight: 260
url: /ko/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

텍스트 필드의 정렬 스타일을 설정합니다.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 정규화된 필드 이름입니다. |
| 정렬 | Int32 | 정렬 스타일 정의이며, FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter 및 FormFieldFacade.AlignRight를 포함합니다. |

### 반환 값

필드를 찾았고 정렬이 설정된 경우 true.

## 예제

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


