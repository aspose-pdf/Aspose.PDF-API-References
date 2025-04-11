---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 속성. 양식을 연결할 때 필드 이름을 고유하게 만들기 위해 추가되는 접미사의 형식입니다. 이 문자열은 숫자로 대체될 NUM 하위 문자열을 포함해야 합니다. 예를 들어 UniqueSuffix가 ABCNUM이면 필드 fieldName의 이름은 fieldNameABC1, fieldNameABC2, fieldNameABC3 등이 됩니다.
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix 속성

양식을 연결할 때 필드 이름을 고유하게 만들기 위해 추가되는 접미사의 형식입니다. 이 문자열은 숫자로 대체될 %NUM% 하위 문자열을 포함해야 합니다. 예를 들어 UniqueSuffix = "ABC%NUM%"이면 필드 "fieldName"의 이름은: fieldNameABC1, fieldNameABC2, fieldNameABC3 등이 됩니다.

```csharp
public string UniqueSuffix { get; set; }
```

## 예제

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)