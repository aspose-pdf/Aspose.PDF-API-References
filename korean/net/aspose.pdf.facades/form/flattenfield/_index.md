---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 지정된 필드를 완전한 필드 이름으로 평탄화합니다. 다른 모든 필드는 변경되지 않습니다. fieldName이 유효하지 않으면 모든 필드는 변경되지 않습니다.
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField 메서드

지정된 필드를 완전한 필드 이름으로 평탄화합니다. 다른 모든 필드는 변경되지 않습니다. fieldName이 유효하지 않으면 모든 필드는 변경되지 않습니다.

```csharp
public void FlattenField(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 평탄화할 필드의 이름입니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)