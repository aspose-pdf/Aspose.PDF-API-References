---
title: "Form.RenameField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 필드의 이름을 변경합니다. AcroForm 필드든 XFA 필드든 상관없습니다."
type: docs
weight: 330
url: /ko/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

필드 이름을 변경합니다. AcroForm 필드든 XFA 필드든 상관없습니다.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 이전 필드 이름 |
| newFieldName | String | 새 필드 이름 |

## 예제

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


