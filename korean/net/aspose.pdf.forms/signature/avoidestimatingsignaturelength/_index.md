---
title: "Signature.AvoidEstimatingSignatureLength"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Signature 속성. 서명의 길이 추정을 피할지 여부를 나타내는 옵션을 가져오고 설정합니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

서명의 길이 추정을 피할지 여부를 나타내는 옵션을 가져오고 설정합니다.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## 비고

서명 문서 전에 서명 길이 추정을 피합니다. [`CustomSignHash`](../customsignhash/) 및 [`ExternalSignature`](../../externalsignature/)을 통해 서명할 때 사용됩니다. [`CustomSignHash`](../customsignhash/)가 [`DefaultSignatureLength`](../defaultsignaturelength/)보다 긴 서명을 반환하면 [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/)이 발생합니다. 기본값은 `false`입니다.

### 또 보기

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


