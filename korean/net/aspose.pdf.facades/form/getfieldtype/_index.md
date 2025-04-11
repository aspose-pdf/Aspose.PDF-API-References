---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 필드의 유형을 반환합니다.
type: docs
weight: 240
url: /ko/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType 메서드

필드의 유형을 반환합니다.

```csharp
public FieldType GetFieldType(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | 문자열 | 필드 이름. |

### 반환 값

필드 유형에 해당하는 FileType 열거형의 요소입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### 참조

* 열거형 [FieldType](../../fieldtype/)
* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)