---
title: "클래스 ExternalSignature"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Forms.ExternalSignature 클래스. X509Certificate2를 사용하여 분리된 PKCS7 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드 토큰을 지원합니다."
type: docs
weight: 5160
url: /ko/net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class

X509Certificate2를 사용하여 분리된 PKCS#7 서명을 생성합니다. 이는 내보낼 수 없는 개인 키가 있는 USB 스마트 카드와 토큰을 지원합니다.

```csharp
public class ExternalSignature : Signature
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | X509Certificate2를 사용하여 분리된 PKCS#7 `(detached)` 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드 및 토큰을 지원합니다. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | X509Certificate2를 base64 문자열로 사용하여 PKCS#7 서명을 생성합니다. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | X509Certificate2를 base64 문자열로 사용하여 PKCS#7 `(detached)` 서명을 생성합니다. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | X509Certificate2를 사용하여 분리된 PKCS#7 서명을 생성합니다. 이는 내보낼 수 없는 개인 키가 있는 USB 스마트 카드와 토큰을 지원합니다. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | X509Certificate2를 사용하여 분리된 PKCS#7 `(detached)` 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드 및 토큰을 지원합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | 문서에 서명하는 사람 또는 기관의 이름입니다. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | 서명의 길이 추정을 피할지 여부를 나타내는 옵션을 가져오고 설정합니다. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | 다이제스트 계산을 위한 정확한 바이트 범위를 설명하는 정수 쌍(시작 바이트 오프셋, 바이트 길이) 배열입니다. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | 서명자를 확인하기 위해 수신자가 서명자에게 연락할 수 있도록 서명자가 제공하는 정보(예: 전화번호)입니다. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | 사용자 정의 외관을 가져오거나 설정합니다. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | 문서 해시를 사용자 정의 서명하기 위한 대리자입니다. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | 서명 시각입니다. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | 서명 데이터의 기본 길이(바이트)를 가져오거나 설정합니다. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | 서명 작업의 CPU 호스트 이름 또는 물리적 위치입니다. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | OCSP 설정을 가져오거나 설정합니다. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | 서명 이유(예: (I agree, Pip B.))입니다. |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | 서명 속성을 표시하거나 숨기도록 강제합니다. ShowProperties가 true인 경우 서명 필드는 미리 정의된 외관 형식을 가집니다(표시할 문자열): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- 여기서 {X}는 X 값에 대한 자리표시자입니다. 또한 서명에 이미지가 있을 경우, 나열된 문자열이 이미지 위에 배치됩니다. ShowProperties는 기본적으로 true입니다. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | 타임스탬프 설정을 가져오거나 설정합니다. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | LTV 검증 플래그를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | 서명에 사용된 서명 알고리즘에 대한 정보를 가져옵니다. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | 이 서명에 대해 문서를 검증하고, 문서가 유효하면 true, 그렇지 않으면 false를 반환합니다. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | 이 서명에 대해 문서를 검증하고, 문서가 유효하면 true, 그렇지 않으면 false를 반환합니다. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(X509Certificate2, ValidationOptions, out ValidationResult) | 이 서명에 대해 문서를 검증하고, 문서가 유효하면 true, 그렇지 않으면 false를 반환합니다. 검증은 외부 공개 키 인증서를 사용하여 수행됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | 개인 키가 포함된 인증서. |

### 또 보기

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


