---
title: "FormEditor.CopyOuterField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 기존 필드를 원본 페이지 번호와 좌표를 유지한 채 한 PDF 문서에서 다른 문서로 복사합니다. 참고: 라디오 박스를 제외한 AcroForm 필드에만 적용됩니다."
type: docs
weight: 160
url: /ko/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

기존 필드를 원본 페이지 번호와 좌표를 유지한 채 한 PDF 문서에서 다른 문서로 복사합니다. 참고: AcroForm 필드에만 적용되며(라디오 박스 제외).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcFileName | String | 복사할 필드가 포함된 PDF 문서의 이름입니다. |
| fieldName | String | 원본 전체 자격 필드 이름입니다. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//source.pdf에서 PdfForm.pdf로 텍스트 필드를 복사합니다.
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

기존 필드를 지정된 페이지 번호와 원본 좌표를 유지한 채 한 PDF 문서에서 다른 문서로 복사합니다. 참고: AcroForm 필드에만 적용되며(라디오 박스 제외).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcFileName | String | 복사할 필드가 포함된 PDF 문서의 이름입니다. |
| fieldName | String | 원본 전체 자격 필드 이름입니다. |
| pageNum | Int32 | 새 필드를 배치할 페이지 번호입니다. -1인 경우 새 필드는 기존 필드와 동일한 페이지에 복사됩니다. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

기존 필드를 지정된 페이지 번호와 좌표를 사용하여 한 PDF 문서에서 다른 문서로 복사합니다. 참고: AcroForm 필드에만 적용되며(라디오 박스 제외).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcFileName | String | 복사할 필드가 포함된 PDF 문서의 이름입니다. |
| fieldName | String | 원본 전체 자격 필드 이름입니다. |
| pageNum | Int32 | 새 필드를 배치할 페이지 번호입니다. -1인 경우 새 필드는 기존 필드와 동일한 페이지에 복사됩니다. |
| 가로좌표 | Single | 새 필드의 가로좌표입니다. -1인 경우 가로좌표는 원본과 동일하게 설정됩니다. |
| 세로좌표 | Single | 새 필드의 y좌표입니다. -1인 경우, y좌표는 원래 값과 동일하게 됩니다. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


