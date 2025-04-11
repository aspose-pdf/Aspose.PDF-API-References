---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature 메서드. MDP 서명으로 문서를 인증합니다. 서명 이유, 연락처 및 위치와 같은 데이터는 Signature 객체 sig의 해당 속성에 의해 제공되어야 합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

MDP 서명으로 문서를 인증합니다. 서명 이유, 연락처 및 위치와 같은 데이터는 Signature 객체 sig의 해당 속성에 의해 제공되어야 합니다.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | 서명이 이루어지는 페이지입니다. |
| SigReason | String | 서명의 이유입니다. |
| SigContact | String | 서명의 연락처입니다. |
| SigLocation | String | 서명의 위치입니다. |
| visible | Boolean | 서명의 가시성입니다. |
| annotRect | Rectangle | 서명의 사각형입니다. |
| docMdpSignature | DocMDPSignature | 서명의 문서 MDP 유형입니다. |

### See Also

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

이미 제공된 서명 필드에 배치된 MDP 서명으로 문서를 인증합니다. 서명하기 전에 서명 필드는 비어 있어야 하며, 즉 필드에는 서명 사전이 포함되어서는 안 됩니다. 따라서 pdf 문서에는 이미 서명 필드가 있어야 하며, 서명을 찍을 위치, 해당 페이지 및 사각형은 서명 이름에 의해 찾아진 서명 필드에서 가져옵니다(see sigName parameter).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sigName | String | 서명 필드의 이름입니다. |
| docMdpSignature | DocMDPSignature | 서명의 유형으로, [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) 및 [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/)가 될 수 있습니다. |

### See Also

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)