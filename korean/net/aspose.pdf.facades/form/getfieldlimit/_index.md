---
title: "Form.GetFieldLimit"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 텍스트 필드의 제한을 가져옵니다"
type: docs
weight: 230
url: /ko/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

텍스트 필드의 제한을 가져옵니다.

```csharp
public int GetFieldLimit(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 정규화된 필드 이름입니다. |

### 반환 값

텍스트 필드에 입력할 수 있는 문자 수 제한을 반환합니다. 설정되지 않은 경우 0을 반환합니다

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


