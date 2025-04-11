---
title: Class SignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.SignatureAlgorithmInfo 클래스. 서명 알고리즘에 대한 정보, 유형, 암호화 표준 및 해시 알고리즘을 포함하는 클래스를 나타냅니다.
type: docs
weight: 10000
url: /ko/net/aspose.pdf.security/signaturealgorithminfo/
---
## SignatureAlgorithmInfo 클래스

서명 알고리즘에 대한 정보, 유형, 암호화 표준 및 해시 알고리즘을 포함하는 클래스를 나타냅니다.

```csharp
public abstract class SignatureAlgorithmInfo
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
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | PDF 문서 서명에 사용되는 서명 알고리즘의 유형을 가져옵니다. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | PDF 문서 서명에 사용되는 암호화 표준을 가져옵니다. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 서명에 사용되는 해시 알고리즘을 가져옵니다. 타임스탬프의 경우, 이는 문서 내용의 해시가 서명되는 해시 알고리즘입니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* 어셈블리 [Aspose.PDF](../../)