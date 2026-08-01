---
title: "FormEditor.SetSubmitFlag"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 제출 버튼의 제출 플래그를 설정합니다."
type: docs
weight: 330
url: /ko/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

제출 버튼의 submit 플래그를 설정합니다.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 제출 버튼의 이름입니다. |
| submitFormFlag | SubmitFormFlag | 제출 플래그. |

### 반환 값

필드를 찾았고 제출 플래그가 성공적으로 설정된 경우 true입니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### 또 보기

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


