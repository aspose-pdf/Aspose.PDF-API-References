---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ExternalSignature 클래스. X509Certificate2를 사용하여 분리된 PKCS7 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드 토큰을 지원합니다.
type: docs
weight: 5040
url: /ko/net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature 클래스

X509Certificate2를 사용하여 분리된 PKCS#7 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드, 토큰을 지원합니다.

```csharp
public class ExternalSignature : Signature
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | X509Certificate2를 사용하여 분리된 PKCS#7 `(detached)` 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드, 토큰을 지원합니다. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | base64 문자열로 X509Certificate2를 사용하여 PKCS#7 서명을 생성합니다. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | base64 문자열로 X509Certificate2를 사용하여 PKCS#7 `(detached)` 서명을 생성합니다. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | X509Certificate2를 사용하여 분리된 PKCS#7 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드, 토큰을 지원합니다. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | X509Certificate2를 사용하여 분리된 PKCS#7 `(detached)` 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드, 토큰을 지원합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | 문서에 서명한 사람 또는 기관의 이름입니다. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 서명의 길이를 추정하지 않도록 설정하는 옵션을 가져오고 설정합니다. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | 다이제스트 계산을 위한 정확한 바이트 범위를 설명하는 정수 쌍의 배열(시작 바이트 오프셋, 바이트 길이)입니다. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 서명자가 서명을 확인하기 위해 수신자가 서명자에게 연락할 수 있도록 제공하는 정보입니다. 예: 전화번호. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | 사용자 정의 모양을 가져오고 설정합니다. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | 문서 해시를 사용자 정의 서명하는 대리자입니다. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 서명 시간입니다. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | 바이트 단위의 서명 데이터에 대한 기본 길이를 가져오거나 설정합니다. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 서명하는 CPU 호스트 이름 또는 물리적 위치입니다. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | ocsp 설정을 가져오고 설정합니다. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 서명의 이유입니다. 예: (동의합니다, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 서명 속성을 표시/숨기도록 강제합니다. ShowProperties가 true인 경우 서명 필드는 미리 정의된 모양 형식을 가집니다 (표현할 문자열): ------------------------------------------- {certificate subject}에 의해 디지털 서명됨 날짜: {signature.Date} 이유: {signature.Reason} 위치: {signature.Location} ------------------------------------------- 여기서 {X}는 X 값의 자리 표시자입니다. 또한 서명에는 이미지가 있을 수 있으며, 이 경우 나열된 문자열이 이미지 위에 배치됩니다. 기본적으로 ShowProperties는 true입니다. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | 타임스탬프 설정을 가져오고 설정합니다. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | ltv 검증 플래그를 가져오고 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 서명에 사용된 서명 알고리즘에 대한 정보를 검색합니다. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | 이 서명에 대해 문서를 검증하고 문서가 유효하면 true를 반환하며, 그렇지 않으면 false를 반환합니다. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | 이 서명에 대해 문서를 검증하고 문서가 유효하면 true를 반환하며, 그렇지 않으면 false를 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | 개인 키가 있는 인증서입니다. |

### 참조

* 클래스 [Signature](../signature/)
* 네임스페이스 [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* 어셈블리 [Aspose.PDF](../../)