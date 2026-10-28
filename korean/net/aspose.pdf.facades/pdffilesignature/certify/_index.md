---
title: "PdfFileSignature.Certify"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileSignature 메서드. 문서를 MDP 서명으로 인증합니다. 서명 이유, 연락처 및 위치와 같은 데이터는 Signature 객체 sig의 해당 속성을 통해 제공되어야 합니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

MDP 서명을 사용하여 문서를 인증합니다. 서명 이유, 연락처 및 위치와 같은 데이터는 Signature 객체 sig의 해당 속성을 통해 제공되어야 합니다.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | Int32 | 서명이 이루어지는 페이지. |
| SigReason | String | 서명의 이유입니다. |
| SigContact | String | 서명의 연락처. |
| SigLocation | String | 서명의 위치. |
| 보이는 | Boolean | 서명의 가시성입니다. |
| annotRect | Rectangle | 서명의 사각형 영역입니다. |
| docMdpSignature | DocMDPSignature | 서명의 문서 MDP 유형. |

### 또 보기

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

이미 제시된 서명 필드에 배치된 MDP 서명을 사용하여 문서를 인증합니다. 서명하기 전에 서명 필드는 비어 있어야 하며, 즉 필드에 서명 사전이 포함되어 있지 않아야 합니다. 따라서 pdf 문서에 이미 서명 필드가 존재하므로 서명을 찍을 위치를 제공할 필요가 없으며, 해당 페이지와 사각형은 서명 이름으로 찾은 서명 필드에서 가져옵니다 (sigName 매개변수 참조).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sigName | String | 서명 필드의 이름. |
| docMdpSignature | DocMDPSignature | 서명의 유형이며, [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) 및 [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) 중 하나일 수 있습니다. |

### 또 보기

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


