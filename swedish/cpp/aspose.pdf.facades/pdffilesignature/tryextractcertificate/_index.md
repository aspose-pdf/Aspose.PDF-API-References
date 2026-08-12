---
title: "Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate metod"
linktitle: "TryExtractCertificate"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate metod. Extraherar signaturens enkla X.509‑certifikat som en ström i C++."
type: docs
weight: 3700
url: /sv/cpp/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## PdfFileSignature::TryExtractCertificate(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::IO::Stream\>\&) method


Extraherar signaturens enda X.509‑certifikat som en ström.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<System::IO::Stream> &stream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |
| ström | System::SharedPtr\<System::IO::Stream\>\& | Om ett certifikat hittades returneras X.509‑certifikatström; annars null. |

### ReturnValue

Ett riktigt certifikat hittades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryExtractCertificate(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) method


Extraherar signaturens enda X.509‑certifikat.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |
| certificate | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Om ett certifikat hittades returneras X.509‑certifikatobjekt; annars null. |

### ReturnValue

Ett riktigt certifikat hittades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
