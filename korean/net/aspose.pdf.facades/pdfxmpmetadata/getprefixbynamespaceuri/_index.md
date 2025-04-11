---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 메서드. 네임스페이스 URI로 접두사를 가져옵니다.
type: docs
weight: 180
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI 메서드

네임스페이스 URI로 접두사를 가져옵니다.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| namespaceURI | 문자열 | 네임스페이스 URI. |

### 반환 값

접두사 값.

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### 참조

* 클래스 [PdfXmpMetadata](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)