---
title: "PdfXmpMetadata.RegisterNamespaceURI"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfXmpMetadata 메서드. 네임스페이스 URI를 등록합니다."
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

namespace URI를 등록합니다.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| prefix | String | 접두사입니다. |
| namespaceURI | String | 네임스페이스 URI입니다. |

## 예제

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### 또 보기

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


