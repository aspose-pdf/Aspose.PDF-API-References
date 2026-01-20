---
title: Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate method
linktitle: TryExtractCertificate
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate method. Extracts signature''s single X.509 certificate as a stream in C++.'
type: docs
weight: 3700
url: /cpp/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## PdfFileSignature::TryExtractCertificate(System::SharedPtr\<SignatureName\>, System::SharedPtr\<System::IO::Stream\>\&) method


Extracts signature's single X.509 certificate as a stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate(System::SharedPtr<SignatureName> signName, System::SharedPtr<System::IO::Stream> &stream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::SharedPtr\<SignatureName\> | The name of signature. |
| stream | System::SharedPtr\<System::IO::Stream\>\& | If a certificate was found returns X.509 single certificate stream; otherwise, null. |

### ReturnValue

True certificate was found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryExtractCertificate(System::SharedPtr\<SignatureName\>, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) method


Extracts signature's single X.509 certificate.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate(System::SharedPtr<SignatureName> signName, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::SharedPtr\<SignatureName\> | The name of signature. |
| certificate | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | If a certificate was found returns X.509 single certificate object; otherwise, null. |

### ReturnValue

True certificate was found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
