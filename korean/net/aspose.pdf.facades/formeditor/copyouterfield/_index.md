---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 기존 필드를 한 PDF 문서에서 다른 문서로 원래 페이지 번호와 좌표로 복사합니다. 주의 라디오 박스를 제외한 AcroForm 필드에만 해당됩니다.
type: docs
weight: 160
url: /ko/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

기존 필드를 한 PDF 문서에서 다른 문서로 원래 페이지 번호와 좌표로 복사합니다. 주의: AcroForm 필드에만 해당됩니다 (라디오 박스 제외).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcFileName | String | 복사할 필드를 포함하는 PDF 문서의 이름입니다. |
| fieldName | String | 원래의 완전한 필드 이름입니다. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

기존 필드를 한 PDF 문서에서 다른 문서로 지정된 페이지 번호와 원래 좌표로 복사합니다. 주의: AcroForm 필드에만 해당됩니다 (라디오 박스 제외).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcFileName | String | 복사할 필드를 포함하는 PDF 문서의 이름입니다. |
| fieldName | String | 원래의 완전한 필드 이름입니다. |
| pageNum | Int32 | 새 필드를 포함할 페이지 번호입니다. -1인 경우, 새 필드는 기존 필드가 호스팅된 동일한 페이지로 복사됩니다. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

기존 필드를 한 PDF 문서에서 다른 문서로 지정된 페이지 번호와 좌표로 복사합니다. 주의: AcroForm 필드에만 해당됩니다 (라디오 박스 제외).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcFileName | String | 복사할 필드를 포함하는 PDF 문서의 이름입니다. |
| fieldName | String | 원래의 완전한 필드 이름입니다. |
| pageNum | Int32 | 새 필드를 포함할 페이지 번호입니다. -1인 경우, 새 필드는 기존 필드가 호스팅된 동일한 페이지로 복사됩니다. |
| abscissa | Single | 새 필드의 x좌표입니다. -1인 경우, x좌표는 원래의 것과 같습니다. |
| ordinate | Single | 새 필드의 y좌표입니다. -1인 경우, y좌표는 원래의 것과 같습니다. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)