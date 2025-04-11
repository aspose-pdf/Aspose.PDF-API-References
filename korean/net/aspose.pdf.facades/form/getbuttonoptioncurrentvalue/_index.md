---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 라디오 버튼 옵션 필드의 현재 값을 반환합니다.
type: docs
weight: 180
url: /ko/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue 메서드

라디오 버튼 옵션 필드의 현재 값을 반환합니다.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | 문자열 | 필드 이름 |

### 반환 값

현재 라디오 그룹 옵션에 대한 문자열 값. 또한 [`GetButtonOptionValues`](../getbuttonoptionvalues/)를 참조하십시오.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)