---
title: "FormEditor.RemoveField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 양식에서 필드를 제거합니다"
type: docs
weight: 210
url: /ko/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

양식에서 필드를 제거합니다.

```csharp
public void RemoveField(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 제거해야 할 필드의 이름. |

## 예제

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


