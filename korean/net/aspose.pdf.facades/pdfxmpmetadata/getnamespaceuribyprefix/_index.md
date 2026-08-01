---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfXmpMetadata 메서드. 접두사로 네임스페이스 URI를 가져옵니다."
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method

접두사로 namespace URI를 가져옵니다.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| prefix | String | 접두사입니다. |

### 반환 값

네임스페이스 URI.

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### 또 보기

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


