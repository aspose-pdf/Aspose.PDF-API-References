---
title: "Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature-metod"
linktitle: "TryVerifySignature"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature-metod. Försök att kontrollera giltigheten för en signatur i C++."
type: docs
weight: 3800
url: /sv/cpp/aspose.pdf.facades/pdffilesignature/tryverifysignature/
---
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Försök att kontrollera giltigheten för en signatur.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | Verifieringsalternativen. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Resultatet av certifikatvalideringen. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Verifieringsresultatet. |

### ReturnValue

Returnerar **true** om signaturen behandlades korrekt. Returnerar **false** om ett fel inträffade under verifieringsprocessen eller om signaturen var korrupt eller komprometterad.
## Anmärkningar



Denna metod låter dig kontrollera signeringscertifikatet med hjälp av OCSP och/eller CRL (certifikatåterkallningslista) för återkallelse. Metoden kontrollerar inte certifikatkedjan och dess giltighet, men den kontrollerar om slutcertifikatet har återkallats.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Försök att kontrollera giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Det offentliga nyckelcertifikatet för verifiering. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | Verifieringsalternativen. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Resultatet av certifikatvalideringen. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Resultatet av verifieringen. |

### ReturnValue

Returnerar **true** om signaturen behandlades korrekt. Returnerar **false** om ett fel inträffade under verifieringsprocessen eller om signaturen var korrupt eller komprometterad.
## Anmärkningar



Denna metod låter dig kontrollera signeringscertifikatet med hjälp av OCSP och/eller CRL (certifikatåterkallningslista) för återkallelse. Metoden kontrollerar inte certifikatkedjan och dess giltighet, men den kontrollerar om slutcertifikatet har återkallats.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Försök att kontrollera giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Det offentliga nyckelcertifikatet för verifiering. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Resultatet av verifieringen. |

### ReturnValue

Returnerar **true** om signaturen behandlades korrekt. Returnerar **false** om ett fel inträffade under verifieringsprocessen eller om signaturen var korrupt eller komprometterad.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Försök att kontrollera giltigheten för en signatur.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | Resultatet av verifieringen. |

### ReturnValue

Returnerar **true** om signaturen behandlades korrekt. Returnerar **false** om ett fel inträffade under verifieringsprocessen eller om signaturen var korrupt eller komprometterad.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
