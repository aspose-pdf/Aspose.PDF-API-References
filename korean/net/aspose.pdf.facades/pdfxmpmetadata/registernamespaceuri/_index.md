---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 메서드. 네임스페이스 URI를 등록합니다.
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI 메서드

네임스페이스 URI를 등록합니다.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| prefix | 문자열 | 접두사. |
| namespaceURI | 문자열 | 네임스페이스 URI. |

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### 참조

* 클래스 [PdfXmpMetadata](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)