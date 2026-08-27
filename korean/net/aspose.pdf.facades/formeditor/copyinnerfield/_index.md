---
title: "FormEditor.CopyInnerField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 지정된 페이지 번호에서 기존 필드를 동일한 위치에 복사합니다. 새 문서는 원본 문서가 가지고 있는 모든 내용을 포함하지만 새로 복사된 필드는 제외합니다."
type: docs
weight: 150
url: /ko/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

기존 필드를 지정된 페이지 번호의 동일한 위치로 복사합니다. 새 문서는 원본 문서의 모든 내용을 포함하지만 새로 복사된 필드는 제외됩니다.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 이전 전체 지정된 필드 이름. |
| newFieldName | String | 새 전체 지정된 필드 이름. null인 경우 fieldName + "~" 로 설정됩니다. |
| pageNum | Int32 | 새 필드를 배치할 페이지 번호입니다. -1인 경우 새 필드는 기존 필드와 동일한 페이지에 복사됩니다. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//두 번째 페이지에 텍스트 필드 복사본을 생성합니다.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

기존 필드를 페이지 번호와 좌표 모두로 지정된 새로운 위치로 복사합니다. 새 문서는 원본 문서의 모든 내용을 포함하지만 새로 복사된 필드는 제외됩니다.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 이전 전체 지정된 필드 이름. |
| newFieldName | String | 새 전체 지정된 필드 이름. null인 경우 fieldName + "~" 로 설정됩니다. |
| pageNum | Int32 | 새 필드를 배치할 페이지 번호입니다. -1인 경우 새 필드는 기존 필드와 동일한 페이지에 복사됩니다. |
| 가로좌표 | Single | 새 필드의 가로좌표입니다. -1인 경우 가로좌표는 원본과 동일하게 설정됩니다. |
| 세로좌표 | Single | 새 필드의 y좌표입니다. -1인 경우, y좌표는 원래 값과 동일하게 됩니다. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//두 번째 페이지에 텍스트 필드 복사본을 생성합니다.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


