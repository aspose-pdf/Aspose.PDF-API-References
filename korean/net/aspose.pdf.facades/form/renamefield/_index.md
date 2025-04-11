---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 필드의 이름을 변경합니다. AcroForm 필드 또는 XFA 필드 모두 가능합니다.
type: docs
weight: 330
url: /ko/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField 메서드

필드의 이름을 변경합니다. AcroForm 필드 또는 XFA 필드 모두 가능합니다.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 이전 필드 이름 |
| newFieldName | String | 새로운 필드 이름 |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)