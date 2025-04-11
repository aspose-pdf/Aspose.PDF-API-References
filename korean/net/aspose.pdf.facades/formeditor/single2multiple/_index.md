---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 단일 행 텍스트 필드를 다중 행 텍스트 필드로 변경합니다.
type: docs
weight: 350
url: /ko/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple 메서드

단일 행 텍스트 필드를 다중 행 텍스트 필드로 변경합니다.

```csharp
public bool Single2Multiple(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 자격이 부여된 필드 이름입니다. |

### 반환 값

성공하면 true를 반환하고, 그렇지 않으면 false를 반환합니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)