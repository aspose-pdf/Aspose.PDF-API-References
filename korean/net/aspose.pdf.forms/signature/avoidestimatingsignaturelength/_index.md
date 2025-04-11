---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Signature 속성. 서명의 길이를 추정하지 않을지 여부를 설정하는 옵션을 가져오고 설정합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength 속성

서명의 길이를 추정하지 않을지 여부를 설정하는 옵션을 가져오고 설정합니다.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## 비고

서명 문서 전에 서명 길이를 추정하지 않습니다. [`CustomSignHash`](../customsignhash/) 및 [`ExternalSignature`](../../externalsignature/)를 통해 서명하는 데 사용됩니다. 만약 [`CustomSignHash`](../customsignhash/)가 [`DefaultSignatureLength`](../defaultsignaturelength/)보다 긴 서명을 반환하면, [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/)이 발생합니다. 기본값은 `false`입니다.

### 참조

* 클래스 [Signature](../)
* 네임스페이스 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 어셈블리 [Aspose.PDF](../../../)