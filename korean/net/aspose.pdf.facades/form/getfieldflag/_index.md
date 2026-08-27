---
title: "Form.GetFieldFlag"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 필드의 플래그를 반환합니다"
type: docs
weight: 220
url: /ko/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag method

필드의 플래그를 반환합니다.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드 이름 |

### 반환 값

속성 플래그 (ReadOnly/ Required/ NoExport

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### 또 보기

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


