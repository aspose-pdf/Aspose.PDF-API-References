---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 필드의 제출 작업 제거
type: docs
weight: 220
url: /ko/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction 메서드

필드의 제출 작업을 제거합니다.

```csharp
public void RemoveFieldAction(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | 문자열 | 필드의 이름. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)