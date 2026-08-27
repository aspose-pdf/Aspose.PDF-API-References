---
title: "FormEditor.RemoveFieldAction"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor method. 필드의 제출 동작을 제거합니다."
type: docs
weight: 220
url: /ko/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction method

필드의 제출 동작을 제거합니다.

```csharp
public void RemoveFieldAction(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드 이름. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


