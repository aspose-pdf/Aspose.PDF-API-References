---
title: "FormEditor.SetSubmitUrl"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 버튼의 URL을 설정합니다."
type: docs
weight: 340
url: /ko/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

버튼의 URL을 설정합니다.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 제출 버튼 이름입니다. |
| url | String | 전체 자격 URL입니다. |

### 반환 값

버튼의 URL이 성공적으로 설정된 경우 true.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


