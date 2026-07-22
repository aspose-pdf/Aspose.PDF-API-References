---
title: "Aspose::Pdf::Facades::PdfFileSignature::VerifySignature-metod"
linktitle: "VerifySignature"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSignature::VerifySignature-metod. Kontrollerar giltigheten för en signatur i C++."
type: docs
weight: 3900
url: /sv/cpp/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&) method


Kontrollerar giltigheten för en signatur.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |

### ReturnValue

Returnerar ett resultat av bool-typ.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Kontrollerar giltigheten för en signatur.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | Verifieringsalternativen. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Resultatet av certifikatvalideringen. |

### ReturnValue

Returnerar ett resultat av bool-typ.
## Anmärkningar



Denna metod låter dig kontrollera signeringscertifikatet med hjälp av OCSP och/eller CRL (certifikatåterkallningslista) för återkallelse. Metoden kontrollerar inte certifikatkedjan och dess giltighet, men den kontrollerar om slutcertifikatet har återkallats.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) method


Kontrollerar giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Det offentliga nyckelcertifikatet för verifiering. |

### ReturnValue

Returnerar ett resultat av bool-typ.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Kontrollerar giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Det offentliga nyckelcertifikatet för verifiering. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | Verifieringsalternativen. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Resultatet av certifikatvalideringen. |

### ReturnValue

Returnerar ett resultat av bool-typ.
## Anmärkningar



Denna metod låter dig kontrollera signeringscertifikatet med hjälp av OCSP och/eller CRL (certifikatåterkallningslista) för återkallelse. Metoden kontrollerar inte certifikatkedjan och dess giltighet, men den kontrollerar om slutcertifikatet har återkallats.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::String\&) method


Kontrollerar giltigheten för en signatur.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::String &signName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::String\& | Namnet på signaturen. |

### ReturnValue

Returnerar ett resultat av bool-typ.

## Deprecated
Använd VerifySignature(SignatureName)-metoden istället.

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::String\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Kontrollerar giltigheten för en signatur.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::String &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::String\& | Namnet på signaturen. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | Verifieringsalternativen. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Resultatet av certifikatvalideringen. |

### ReturnValue

Returnerar ett resultat av bool-typ.
## Anmärkningar


## Deprecated
Använd VerifySignature(SignatureName, ValidationOptions, out ValidationResult)-metoden istället.


Denna metod låter dig kontrollera signeringscertifikatet med hjälp av OCSP och/eller CRL (certifikatåterkallningslista) för återkallelse. Metoden kontrollerar inte certifikatkedjan och dess giltighet, men den kontrollerar om slutcertifikatet har återkallats.
## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
