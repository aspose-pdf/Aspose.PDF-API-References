---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 필드 이름에 따라 라디오 버튼 옵션 필드 및 관련 값을 가져옵니다. 이 메서드는 라디오 버튼 그룹에 의미가 있습니다.
type: docs
weight: 190
url: /ko/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues 메서드

필드 이름에 따라 라디오 버튼 옵션 필드 및 관련 값을 가져옵니다. 이 메서드는 라디오 버튼 그룹에 의미가 있습니다.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드 이름 |

### 반환 값

양식 항목 이름으로 키가 지정된 옵션 값의 해시 테이블

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)