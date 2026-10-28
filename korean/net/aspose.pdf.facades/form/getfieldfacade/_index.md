---
title: "Form.GetFieldFacade"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 모든 외관 속성을 포함하는 FrofmFieldFacade 객체를 반환합니다"
type: docs
weight: 210
url: /ko/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

모든 외관 속성을 포함하는 FrofmFieldFacade 객체를 반환합니다.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 읽을 필드의 이름. |

### 반환 값

FormFieldFacade 객체

### 또 보기

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


