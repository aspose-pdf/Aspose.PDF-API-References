---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 텍스트 상자 필드를 텍스트 값으로 채우고 문서를 저장합니다. 서명된 문서에 관련이 있습니다. 주의: 텍스트 상자에만 적용됩니다. 필드 이름과 값 모두 대소문자를 구분합니다.
type: docs
weight: 140
url: /ko/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields 메서드

텍스트 상자 필드를 텍스트 값으로 채우고 문서를 저장합니다. 서명된 문서에 관련이 있습니다. 주의: 텍스트 상자에만 적용됩니다. 필드 이름과 값 모두 대소문자를 구분합니다.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldNames | String[] | 필드의 이름. |
| fieldValues | String[] | 필드의 새 값. |
| output | Stream& | 문서가 저장될 스트림. |

### 반환 값

필드를 찾고 성공적으로 채운 경우 true를 반환합니다.

## 예제

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)