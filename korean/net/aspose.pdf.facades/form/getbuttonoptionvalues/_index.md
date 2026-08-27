---
title: "Form.GetButtonOptionValues"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 필드 이름을 기준으로 라디오 버튼 옵션 필드와 관련 값을 가져옵니다. 이 메서드는 라디오 버튼 그룹에 의미가 있습니다."
type: docs
weight: 190
url: /ko/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

필드 이름을 기준으로 라디오 버튼 옵션 필드와 관련 값을 가져옵니다. 이 메서드는 라디오 버튼 그룹에 의미가 있습니다.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드 이름 |

### 반환 값

폼 항목 이름을 키로 하는 옵션 값 해시 테이블

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


