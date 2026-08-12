---
title: "Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate método"
linktitle: "ExtractCertificate"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate método. Extrae el único certificado X.509 de la firma como un flujo en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf.facades/pdffilesignature/extractcertificate/
---
## PdfFileSignature::ExtractCertificate(const System::SharedPtr\<SignatureName\>\&) method


Extrae el único certificado X.509 de la firma como un flujo.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate(const System::SharedPtr<SignatureName> &signName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |

### ReturnValue

Si se encontró un certificado, devuelve un único certificado X.509; de lo contrario, null.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::ExtractCertificate(const System::String\&) method


Extrae el único certificado X.509 de la firma como un flujo.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate(const System::String &signName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::String\& | El nombre de la firma. |

### ReturnValue

Si se encontró el certificado, devuelve el certificado X.509 único; de lo contrario, null.

## Deprecated
Utilice el método ExtractCertificate(SignatureName) en su lugar.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
