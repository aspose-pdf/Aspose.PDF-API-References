---
title: Aspose::Pdf::Facades::PdfFileSignature::Certify method
linktitle: Certify
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::Certify method. Certify the document with the MDP signature. Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.facades/pdffilesignature/certify/
---
## PdfFileSignature::Certify(int32_t, System::String, System::String, System::String, bool, System::Drawing::Rectangle, System::SharedPtr\<Forms::DocMDPSignature\>) method


Certify the document with the MDP signature. Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Certify(int32_t page, System::String SigReason, System::String SigContact, System::String SigLocation, bool visible, System::Drawing::Rectangle annotRect, System::SharedPtr<Forms::DocMDPSignature> docMdpSignature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The page on which signature is made. |
| SigReason | System::String | The reason of signature. |
| SigContact | System::String | The contact of signature. |
| SigLocation | System::String | The location of signature. |
| visible | bool | The visiblity of signature. |
| annotRect | System::Drawing::Rectangle | The rect of signature. |
| docMdpSignature | System::SharedPtr\<Forms::DocMDPSignature\> | The document MDP type of the signature. |

## See Also

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Certify(System::String, System::SharedPtr\<Forms::DocMDPSignature\>) method


Certify the document with the MDP signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see sigName parameter).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Certify(System::String sigName, System::SharedPtr<Forms::DocMDPSignature> docMdpSignature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| sigName | System::String | The name of the signature field. |
| docMdpSignature | System::SharedPtr\<Forms::DocMDPSignature\> | The type of the signature, could be [Aspose::Pdf::Forms::PKCS1](../../../aspose.pdf.forms/pkcs1/), [Aspose::Pdf::Forms::PKCS7](../../../aspose.pdf.forms/pkcs7/) and [Aspose::Pdf::Forms::PKCS7Detached](../../../aspose.pdf.forms/pkcs7detached/) |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
