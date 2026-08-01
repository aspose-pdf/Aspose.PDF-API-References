---
title: "FormEditor.Single2Multiple"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 단일 라인 텍스트 필드를 다중 라인 필드로 변경합니다."
type: docs
weight: 350
url: /ko/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

단일 행 텍스트 필드를 다중 행으로 변경합니다.

```csharp
public bool Single2Multiple(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 정규화된 필드 이름입니다. |

### 반환 값

성공하면 true를 반환하고, 그렇지 않으면 false를 반환합니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


