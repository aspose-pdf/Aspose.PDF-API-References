---
title: "Form.GetFieldType"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 필드 유형을 반환합니다."
type: docs
weight: 240
url: /ko/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType method

필드 유형을 반환합니다.

```csharp
public FieldType GetFieldType(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드 이름. |

### 반환 값

필드 유형에 해당하는 FileType 열거형 요소입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### 또 보기

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


