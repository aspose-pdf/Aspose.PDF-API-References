---
title: "Método Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate"
linktitle: "TryExtractCertificate"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate. Extrae el único certificado X.509 de la firma como un flujo en C++."
type: docs
weight: 3700
url: /es/cpp/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## PdfFileSignature::TryExtractCertificate(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::IO::Stream\>\&) method


Extrae el único certificado X.509 de la firma como un flujo.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<System::IO::Stream> &stream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |
| flujo | System::SharedPtr\<System::IO::Stream\>\& | Si se encontró un certificado, devuelve el flujo del certificado X.509 único; de lo contrario, null. |

### ReturnValue

Se encontró un certificado válido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryExtractCertificate(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) method


Extrae el certificado X.509 único de la firma.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryExtractCertificate(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |
| certificado | System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | Si se encontró un certificado, devuelve el objeto del certificado X.509 único; de lo contrario, null. |

### ReturnValue

Se encontró un certificado válido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
