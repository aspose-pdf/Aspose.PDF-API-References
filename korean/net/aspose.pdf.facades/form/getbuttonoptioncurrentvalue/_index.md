---
title: "Form.GetButtonOptionCurrentValue"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 라디오 버튼 옵션 필드의 현재 값을 반환합니다"
type: docs
weight: 180
url: /ko/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue method

라디오 버튼 옵션 필드의 현재 값을 반환합니다.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드 이름 |

### 반환 값

현재 라디오 그룹 옵션의 문자열 값입니다. 또한 [`GetButtonOptionValues`](../getbuttonoptionvalues/)를 참조하십시오

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


