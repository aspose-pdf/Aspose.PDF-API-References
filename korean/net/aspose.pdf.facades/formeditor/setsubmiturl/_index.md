---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 버튼의 URL을 설정합니다.
type: docs
weight: 340
url: /ko/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl 메서드

버튼의 URL을 설정합니다.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 제출 버튼 이름. |
| url | String | 완전한 URL. |

### 반환 값

버튼의 URL이 성공적으로 설정되면 true를 반환합니다.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)