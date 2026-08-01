---
title: "클래스 TimestampAlgorithmInfo"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Security.TimestampAlgorithmInfo 클래스. 타임스탬프 서명 알고리즘에 대한 정보를 제공하는 클래스를 나타냅니다."
type: docs
weight: 10210
url: /ko/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo class

타임스탬프 서명 알고리즘에 대한 정보를 제공하는 클래스를 나타냅니다.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | 서명 필드의 이름을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | 현재 정보 객체를 문자열 표현으로 변환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | PDF 문서 서명에 사용되는 서명 알고리즘 유형을 가져옵니다. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | 문서 내용을 해시한 후 [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/)을 사용해 서명하는 해시 알고리즘을 가져옵니다. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | PDF 문서 서명에 사용되는 암호 표준을 가져옵니다. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 서명에 사용되는 다이제스트 해시 알고리즘을 가져옵니다. 타임스탬프의 경우, 이는 문서 내용의 해시가 서명되는 다이제스트 해시 알고리즘입니다. |

### 또 보기

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


