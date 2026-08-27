---
title: "Form.GetField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 필드 이름에 따라 필드 값을 가져옵니다."
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

필드 이름에 따라 필드 값을 가져옵니다.

```csharp
public string GetField(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 전체 한정된 필드 이름. |

### 반환 값

필드 값입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


