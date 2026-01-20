---
title: Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate method
linktitle: ExtractCertificate
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate method. Extracts signature''s single X.509 certificate as a stream in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.facades/pdffilesignature/extractcertificate/
---
## PdfFileSignature::ExtractCertificate(System::SharedPtr\<SignatureName\>) method


Extracts signature's single X.509 certificate as a stream.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate(System::SharedPtr<SignatureName> signName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::SharedPtr\<SignatureName\> | The name of signature. |

### ReturnValue

If a certificate was found returns X.509 single certificate; otherwise, null.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::ExtractCertificate(System::String) method


Extracts signature's single X.509 certificate as a stream.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate(System::String signName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::String | The name of signature. |

### ReturnValue

If certificate was found returns X.509 single certificate; otherwise, null.

## Deprecated
Use ExtractCertificate(SignatureName) method instead. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
