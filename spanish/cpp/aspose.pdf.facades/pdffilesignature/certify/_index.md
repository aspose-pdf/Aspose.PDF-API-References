---
title: "Método Aspose::Pdf::Facades::PdfFileSignature::Certify"
linktitle: "Certify"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfFileSignature::Certify. Certifica el documento con la firma MDP que se coloca en un campo de firma ya existente. Antes de firmar, el campo de firma debe estar vacío, es decir, no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar la ubicación para estampar la firma, la página y el rectángulo correspondientes se obtienen del campo de firma que se encuentra mediante el nombre de la firma (ver el parámetro sigName) en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.facades/pdffilesignature/certify/
---
## PdfFileSignature::Certify(const System::String\&, const System::SharedPtr\<Forms::DocMDPSignature\>\&) method


Certifica el documento con la firma MDP que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento pdf ya tiene un campo de firma; no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver el parámetro sigName).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Certify(const System::String &sigName, const System::SharedPtr<Forms::DocMDPSignature> &docMdpSignature)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sigName | const System::String\& | El nombre del campo de firma. |
| docMdpSignature | const System::SharedPtr\<Forms::DocMDPSignature\>\& | El tipo de la firma, puede ser [Aspose::Pdf::Forms::PKCS1](../../../aspose.pdf.forms/pkcs1/), [Aspose::Pdf::Forms::PKCS7](../../../aspose.pdf.forms/pkcs7/) y [Aspose::Pdf::Forms::PKCS7Detached](../../../aspose.pdf.forms/pkcs7detached/) |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Certify(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::DocMDPSignature\>\&) method


Certifica el documento con la firma MDP. Datos como el motivo de la firma, contacto y ubicación deben proporcionarse mediante las propiedades correspondientes del objeto Signature sig.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Certify(int32_t page, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::DocMDPSignature> &docMdpSignature)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | La página en la que se realiza la firma. |
| SigReason | const System::String\& | La razón de la firma. |
| SigContact | const System::String\& | El contacto de la firma. |
| SigLocation | const System::String\& | La ubicación de la firma. |
| visible | bool | La visibilidad de la firma. |
| annotRect | System::Drawing::Rectangle | El rectángulo de la firma. |
| docMdpSignature | const System::SharedPtr\<Forms::DocMDPSignature\>\& | El tipo MDP del documento de la firma. |

## Ver también

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
