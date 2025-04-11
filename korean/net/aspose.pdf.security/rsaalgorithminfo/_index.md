---
title: Class RsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.RsaAlgorithmInfo 클래스. RSA 서명 알고리즘에 대한 정보를 나타내는 클래스입니다.
type: docs
weight: 9990
url: /ko/net/aspose.pdf.security/rsaalgorithminfo/
---
## RsaAlgorithmInfo class

RSA 서명 알고리즘에 대한 정보를 나타내는 클래스입니다.

```csharp
public sealed class RsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
```

## Properties

| Name | Description |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | 서명 필드의 이름을 가져옵니다. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | 현재 정보 객체를 문자열 표현으로 변환합니다. |

## Fields

| Name | Description |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | PDF 문서 서명에 사용되는 서명 알고리즘의 유형을 가져옵니다. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | PDF 문서 서명에 사용되는 암호화 표준을 가져옵니다. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 서명에 사용되는 다이제스트 해시 알고리즘을 가져옵니다. 타임스탬프의 경우, 이는 문서 내용의 해시가 서명되는 다이제스트 해시 알고리즘입니다. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | 서명 알고리즘에 의해 사용되는 암호화 키의 크기를 가져옵니다. |

### See Also

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)