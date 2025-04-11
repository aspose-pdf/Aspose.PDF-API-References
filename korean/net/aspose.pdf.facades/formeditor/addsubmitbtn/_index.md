---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 양식에 제출 버튼 추가
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn 메서드

양식에 제출 버튼을 추가합니다.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 새 버튼의 이름. |
| page | Int32 | 버튼이 배치될 페이지. |
| label | String | 버튼 캡션. |
| url | String | 제출 버튼의 URL. |
| llx | Single | 왼쪽 아래 모서리의 x 좌표. |
| lly | Single | 왼쪽 아래 모서리의 y 좌표. |
| urx | Single | 오른쪽 위 모서리의 x 좌표. |
| ury | Single | 오른쪽 위 모서리의 y 좌표. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)