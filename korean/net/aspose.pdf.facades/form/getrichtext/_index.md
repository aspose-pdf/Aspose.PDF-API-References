---
title: "Form.GetRichText"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 각 문자에 대한 서식 정보를 포함한 Rich Text 필드 값을 가져옵니다."
type: docs
weight: 260
url: /ko/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

리치 텍스트 필드의 값을 가져오며, 각 문자에 대한 서식 정보를 포함합니다.

```csharp
public string GetRichText(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | Rich Text 필드의 전체 지정 필드 이름. |

### 반환 값

Rich Text 필드의 서식 정보를 포함하는 문자열을 반환합니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


