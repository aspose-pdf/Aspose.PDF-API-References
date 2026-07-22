---
title: "Aspose::Pdf::Forms::Signature::TryVerify metod"
linktitle: "TryVerify"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Signature::TryVerify metod. Försök att verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false i C++."
type: docs
weight: 3000
url: /sv/cpp/aspose.pdf.forms/signature/tryverify/
---
## Signature::TryVerify(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Försök att verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | Verifieringsalternativen. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Resultatet av certifikatvalideringen. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Verifieringsresultatet. |

### ReturnValue

Returnerar true om signaturen behandlades korrekt. Returnerar false om ett fel inträffade under verifieringsprocessen eller om signaturen var korrupt eller komprometterad.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::TryVerify(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Försök att verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. Verifieringen utförs med hjälp av det externa offentliga nyckelcertifikatet.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Det offentliga nyckelcertifikatet för verifiering. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | Verifieringsalternativen. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Resultatet av certifikatvalideringen. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Verifieringsresultatet. |

### ReturnValue

Returnerar true om signaturen behandlades korrekt. Returnerar false om ett fel inträffade under verifieringsprocessen eller om signaturen var korrupt eller komprometterad.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::TryVerify(System::SharedPtr\<Security::VerificationResult\>\&) method


Försök att verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Verifieringsresultatet. |

### ReturnValue

Returnerar true om signaturen behandlades korrekt. Returnerar false om ett fel inträffade under verifieringsprocessen eller om signaturen var korrupt eller komprometterad.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
