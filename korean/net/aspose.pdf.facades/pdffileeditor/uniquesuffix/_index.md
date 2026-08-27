---
title: "PdfFileEditor.UniqueSuffix"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 속성. 양식이 연결될 때 필드 이름에 추가되어 고유하게 만드는 접미사의 형식입니다. 이 문자열은 숫자로 대체될 NUM 부분 문자열을 포함해야 합니다. 예를 들어 UniqueSuffix가 ABCNUM이면 필드 fieldName의 이름은 fieldNameABC1, fieldNameABC2, fieldNameABC3 등으로 생성됩니다."
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

양식을 연결할 때 필드 이름을 고유하게 만들기 위해 추가되는 접미사의 형식입니다. 이 문자열은 숫자로 대체될 %NUM% 부분을 포함해야 합니다. 예를 들어 UniqueSuffix = "ABC%NUM%"인 경우 필드 "fieldName"의 이름은 fieldNameABC1, fieldNameABC2, fieldNameABC3 등으로 됩니다.

```csharp
public string UniqueSuffix { get; set; }
```

## 예제

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


