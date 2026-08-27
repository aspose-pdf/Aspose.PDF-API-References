---
title: "Form.GetFullFieldName"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 짧은 필드 이름에 따라 전체 필드 이름을 가져옵니다"
type: docs
weight: 250
url: /ko/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

짧은 필드 이름에 따라 전체 필드 이름을 가져옵니다.

```csharp
public string GetFullFieldName(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 전체 한정된 필드 이름. |

### 반환 값

전체 필드 이름입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


