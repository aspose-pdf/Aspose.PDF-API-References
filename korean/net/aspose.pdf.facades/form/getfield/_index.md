---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 필드 이름에 따라 필드 값을 가져옵니다.
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField 메서드

필드 이름에 따라 필드 값을 가져옵니다.

```csharp
public string GetField(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | 문자열 | 완전한 필드 이름입니다. |

### 반환 값

필드의 값입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)