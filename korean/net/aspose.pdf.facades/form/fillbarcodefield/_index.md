---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 완전한 필드 이름에 따라 바코드 필드를 채웁니다.
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField 메서드

완전한 필드 이름에 따라 바코드 필드를 채웁니다.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 완전한 필드 이름입니다. |
| data | String | 새로운 바코드 값입니다. |

### 반환 값

채우기가 성공하면 true를 반환하고, 그렇지 않으면 false를 반환합니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)