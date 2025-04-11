---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 텍스트 필드의 제한을 가져옵니다.
type: docs
weight: 230
url: /ko/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit 메서드

텍스트 필드의 제한을 가져옵니다.

```csharp
public int GetFieldLimit(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 자격이 부여된 필드 이름입니다. |

### 반환 값

텍스트 필드에 입력할 수 있는 문자 수의 제한을 반환합니다. 설정되지 않은 경우 0을 반환합니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)