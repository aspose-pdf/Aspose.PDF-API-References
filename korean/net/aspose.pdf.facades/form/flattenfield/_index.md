---
title: "Form.FlattenField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 완전한 필드 이름을 사용하여 지정된 필드를 평탄화합니다. 다른 필드는 변경되지 않습니다. fieldName이 유효하지 않으면 모든 필드가 변경되지 않은 상태로 유지됩니다."
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

전체 한정 필드 이름으로 지정된 필드를 플랫하게 만듭니다. 다른 필드는 변경되지 않습니다. fieldName이 유효하지 않으면 모든 필드가 변경되지 않은 상태로 유지됩니다.

```csharp
public void FlattenField(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 평탄화될 필드의 이름. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


