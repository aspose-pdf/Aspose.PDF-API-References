---
title: "열거형 ValidationMethod"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Security.ValidationMethod 열거형. 인증서 검증에 사용되는 방법을 정의한 열거형을 나타냅니다."
type: docs
weight: 10230
url: /ko/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod enumeration

인증서 검증에 사용되는 방법을 정의한 열거형을 나타냅니다.

```csharp
public enum ValidationMethod
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | 인증서 검증에 가장 적합한 방법을 자동으로 결정합니다. |
| Ocsp | `1` | 인증서 검증에 온라인 인증서 상태 프로토콜(OCSP)을 사용합니다. OCSP는 발급 인증 기관(CA)에 직접 질의하여 인증서의 검증 상태를 제공하는 프로토콜입니다. |
| Crl | `2` | 인증서 폐기 목록(CRL) 방법을 사용하여 인증서를 검증합니다. |
| All | `3` | 인증서 검증을 위해 사용 가능한 모든 방법(OCSP 및 CRL)을 사용합니다. |

### 또 보기

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


