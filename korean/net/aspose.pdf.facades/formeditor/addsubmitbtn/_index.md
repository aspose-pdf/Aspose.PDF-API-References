---
title: "FormEditor.AddSubmitBtn"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 양식에 제출 버튼을 추가합니다"
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

양식에 제출 버튼을 추가합니다.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 새 버튼의 이름. |
| 페이지 | Int32 | 버튼이 배치될 페이지. |
| label | String | 버튼 캡션. |
| url | String | 제출 버튼의 URL. |
| llx | Single | 좌하단 모서리의 가로 좌표. |
| lly | Single | 좌하단 모서리의 세로 좌표. |
| urx | Single | 우상단 모서리의 가로 좌표. |
| ury | Single | 우상단 모서리의 세로 좌표. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


