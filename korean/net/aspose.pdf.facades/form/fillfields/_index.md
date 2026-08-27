---
title: "Form.FillFields"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 텍스트 박스 필드에 텍스트 값을 채우고 문서를 저장합니다. 서명된 문서에 적용됩니다. 텍스트 박스에만 적용됩니다. 필드 이름과 값은 대소문자를 구분합니다."
type: docs
weight: 140
url: /ko/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

텍스트 박스 필드를 텍스트 값으로 채우고 문서를 저장합니다. 서명된 문서에 해당됩니다. 참고: 텍스트 박스에만 적용됩니다. 필드 이름과 값은 대소문자를 구분합니다.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldNames | String[] | 필드 이름들. |
| fieldValues | String[] | 필드의 새로운 값들. |
| output | Stream& | 문서가 저장될 스트림. |

### 반환 값

필드를 찾았고 성공적으로 채워졌다면 true.

## 예제

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


