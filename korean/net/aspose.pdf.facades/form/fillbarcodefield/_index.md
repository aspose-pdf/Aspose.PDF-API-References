---
title: "Form.FillBarcodeField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 바코드 필드를 전체 지정된 필드 이름에 따라 채웁니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

전체 한정 필드 이름에 따라 바코드 필드를 채웁니다.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 전체 한정된 필드 이름. |
| data | String | 새 바코드 값입니다. |

### 반환 값

채우기가 성공하면 true를 반환하고, 그렇지 않으면 false를 반환합니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


