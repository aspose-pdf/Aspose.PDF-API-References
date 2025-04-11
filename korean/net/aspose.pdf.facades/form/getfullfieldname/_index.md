---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 짧은 필드 이름에 따라 전체 필드 이름을 가져옵니다.
type: docs
weight: 250
url: /ko/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName 메서드

짧은 필드 이름에 따라 전체 필드 이름을 가져옵니다.

```csharp
public string GetFullFieldName(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 전체 자격 필드 이름입니다. |

### 반환 값

전체 필드 이름입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)