---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 모든 문자에 대한 형식 정보가 포함된 Rich Text 필드의 값을 가져옵니다.
type: docs
weight: 260
url: /ko/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText 메서드

모든 문자에 대한 형식 정보가 포함된 Rich Text 필드의 값을 가져옵니다.

```csharp
public string GetRichText(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | 문자열 | Rich Text 필드의 완전한 자격 필드 이름입니다. |

### 반환 값

Rich Text 필드의 형식 정보를 포함하는 문자열을 반환합니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)