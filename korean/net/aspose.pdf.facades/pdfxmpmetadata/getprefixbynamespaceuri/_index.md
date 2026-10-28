---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfXmpMetadata 메서드. 네임스페이스 URI에 따라 접두사를 가져옵니다."
type: docs
weight: 180
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

namespace URI로부터 접두사를 가져옵니다.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| namespaceURI | String | 네임스페이스 URI. |

### 반환 값

접두사 값.

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### 또 보기

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


