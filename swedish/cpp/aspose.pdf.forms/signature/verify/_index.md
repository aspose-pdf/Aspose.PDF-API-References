---
title: "Aspose::Pdf::Forms::Signature::Verify metod"
linktitle: "Verify"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Signature::Verify metod. Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false i C++."
type: docs
weight: 3100
url: /sv/cpp/aspose.pdf.forms/signature/verify/
---
## Signature::Verify() method


Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify()
```


### ReturnValue

true om dokumentet är giltigt.

## Se även

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Verify(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify(const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | Verifieringsalternativen. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Resultatet av certifikatvalideringen. |

### ReturnValue

true om dokumentet är giltigt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Verify(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt annars false. Verifieringen utförs med hjälp av det externa offentliga nyckelcertifikatet.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Det offentliga nyckelcertifikatet för verifiering. |
| options | const System::SharedPtr\<Security::ValidationOptions\>\& | Verifieringsalternativen. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | Resultatet av certifikatvalideringen. |

### ReturnValue

true om dokumentet är giltigt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
