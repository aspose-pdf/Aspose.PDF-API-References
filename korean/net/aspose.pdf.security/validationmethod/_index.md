---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMethod 열거형. 인증서 검증에 사용되는 방법을 정의하는 열거형을 나타냅니다.
type: docs
weight: 10050
url: /ko/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod 열거형

인증서 검증에 사용되는 방법을 정의하는 열거형을 나타냅니다.

```csharp
public enum ValidationMethod
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | 인증서 검증을 위한 최상의 방법을 자동으로 결정합니다. |
| Ocsp | `1` | 인증서 검증을 위해 온라인 인증서 상태 프로토콜(OCSP)을 사용합니다. OCSP는 발급 인증 기관(CA)에 직접 쿼리하여 인증서의 검증 상태를 제공하는 프로토콜입니다. |
| Crl | `2` | 인증서 폐기 목록(CRL) 방법을 사용하여 인증서를 검증합니다. |
| All | `3` | 인증서 검증을 위해 모든 사용 가능한 방법(OCSP 및 CRL)을 사용합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* 어셈블리 [Aspose.PDF](../../)