---
title: "Aspose.Pdf.Security"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Security 네임스페이스는 암호화 및 디지털 서명에 사용되는 클래스를 포함합니다."
type: docs
weight: 210
url: /ko/net/aspose.pdf.security/
---
**Aspose.Pdf.Security** 네임스페이스에는 암호화 및 디지털 서명에 사용되는 클래스가 포함됩니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [CertificateEncryptionOptions](./certificateencryptionoptions/) | 인증서 기반 암호화 방식을 사용하여 PDF 문서의 암호화 옵션을 지정하는 클래스를 나타냅니다. 암호화된 PDF 문서를 열 때 사용됩니다. |
| [DsaAlgorithmInfo](./dsaalgorithminfo/) | DSA 서명 알고리즘에 대한 정보를 제공하는 클래스를 나타냅니다. |
| [EcdsaAlgorithmInfo](./ecdsaalgorithminfo/) | ECDSA 서명 알고리즘에 대한 정보를 제공하는 클래스를 나타냅니다. |
| [EncryptionParameters](./encryptionparameters/) | 암호화 매개변수 클래스를 나타냅니다. |
| [KeyedSignatureAlgorithmInfo](./keyedsignaturealgorithminfo/) | 키드 서명 알고리즘에 대한 정보를 제공하는 클래스를 나타냅니다. |
| [RsaAlgorithmInfo](./rsaalgorithminfo/) | RSA 서명 알고리즘에 대한 정보를 제공하는 클래스를 나타냅니다. |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/) | 서명 알고리즘에 대한 정보를 제공하는 클래스를 나타내며, 여기에는 유형, 암호 표준 및 다이제스트 해시 알고리즘이 포함됩니다. |
| [SignatureLengthMismatchException](./signaturelengthmismatchexception/) | PDF 서명 중 발생하는 오류를 나타냅니다. 문서에 서명하기 위해 [`SignHash`](../aspose.pdf.forms/signhash/)을 사용했을 때 실제 서명 길이가 [`DefaultSignatureLength`](../aspose.pdf.forms/signature/defaultsignaturelength/) 옵션에 지정된 길이보다 큰 경우에 발생합니다. |
| [TimestampAlgorithmInfo](./timestampalgorithminfo/) | 타임스탬프 서명 알고리즘에 대한 정보를 제공하는 클래스를 나타냅니다. |
| [UnknownSignatureAlgorithmInfo](./unknownsignaturealgorithminfo/) | 알 수 없는 서명 알고리즘 정보를 제공하는 클래스를 나타냅니다. |
| [ValidationOptions](./validationoptions/) | PDF 문서에서 디지털 서명을 검증하기 위한 옵션을 나타냅니다. |
| [ValidationResult](./validationresult/) | 인증서에 대한 검증 프로세스 결과를 나타냅니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [ICustomSecurityHandler](./icustomsecurityhandler/) | 맞춤형 보안 핸들러 인터페이스입니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [CryptographicStandard](./cryptographicstandard/) | PDF 문서를 보호하기 위한 사용 가능한 암호화 표준을 나타냅니다. |
| [SignatureAlgorithmType](./signaturealgorithmtype/) | 디지털 서명에 사용되는 서명 알고리즘 유형을 열거합니다. |
| [ValidationMethod](./validationmethod/) | 인증서 검증에 사용되는 방법을 정의한 열거형을 나타냅니다. |
| [ValidationMode](./validationmode/) | PDF 서명 검증 프로세스에 대한 검증 모드를 지정합니다. |
| [ValidationStatus](./validationstatus/) | 인증서 검증의 검증 상태를 나타냅니다. |


