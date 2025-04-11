---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 메서드. 접두사로 네임스페이스 URI를 가져옵니다.
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix 메서드

접두사로 네임스페이스 URI를 가져옵니다.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| prefix | String | 접두사. |

### 반환 값

네임스페이스 URI.

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### 참조

* 클래스 [PdfXmpMetadata](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)