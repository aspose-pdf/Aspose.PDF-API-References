---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 모든 외관 속성을 포함하는 FrofmFieldFacade 객체를 반환합니다.
type: docs
weight: 210
url: /ko/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade 메서드

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
| fieldName | 문자열 | 읽을 필드의 이름. |

### 반환 값

FormFieldFacade 객체

### 참조

* 클래스 [FormFieldFacade](../../formfieldfacade/)
* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)