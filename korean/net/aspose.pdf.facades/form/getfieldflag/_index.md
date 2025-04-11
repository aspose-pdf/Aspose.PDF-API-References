---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 필드의 플래그를 반환합니다.
type: docs
weight: 220
url: /ko/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag 메서드

필드의 플래그를 반환합니다.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | 문자열 | 필드 이름 |

### 반환 값

속성 플래그 (읽기 전용/필수/내보내기 없음)

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### 참조

* 열거형 [PropertyFlag](../../propertyflag/)
* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)