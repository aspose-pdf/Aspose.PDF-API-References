---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 양식에서 필드를 제거합니다.
type: docs
weight: 210
url: /ko/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField 메서드

양식에서 필드를 제거합니다.

```csharp
public void RemoveField(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | 문자열 | 제거해야 하는 필드의 이름입니다. |

## 예제

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)