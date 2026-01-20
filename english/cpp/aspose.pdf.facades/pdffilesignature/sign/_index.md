---
title: Aspose::Pdf::Facades::PdfFileSignature::Sign method
linktitle: Sign
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::Sign method. Sign the document with the given type signature in C++.'
type: docs
weight: 3600
url: /cpp/aspose.pdf.facades/pdffilesignature/sign/
---
## PdfFileSignature::Sign(int32_t, bool, System::Drawing::Rectangle, System::SharedPtr\<Forms::Signature\>) method


Sign the document with the given type signature.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, bool visible, System::Drawing::Rectangle annotRect, System::SharedPtr<Forms::Signature> sig)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The page number on which signature is made. |
| visible | bool | The visiblity of signature. |
| annotRect | System::Drawing::Rectangle | The rect of signature. |
| sig | System::SharedPtr\<Forms::Signature\> | The type of the signature, could be PKCS1, PKCS7 and PKCS7Detached. Such data as signature reason, contact and location must be already present in this object (see corresponding properties). |

## See Also

* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, System::String, System::String, System::String, System::String, bool, System::Drawing::Rectangle, System::SharedPtr\<Forms::Signature\>) method


Sign the document with the given type signature which is placed in already presented signature field. Before signing pdf document should already has signature field, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, System::String SigName, System::String SigReason, System::String SigContact, System::String SigLocation, bool visible, System::Drawing::Rectangle annotRect, System::SharedPtr<Forms::Signature> sig)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The page number on which signature is made. |
| SigName | System::String | The name of the signature field. |
| SigReason | System::String | The reason of signature. |
| SigContact | System::String | The contact of signature. |
| SigLocation | System::String | The location of signature. |
| visible | bool | The visiblity of signature. |
| annotRect | System::Drawing::Rectangle | The rect of signature. |
| sig | System::SharedPtr\<Forms::Signature\> | The type of the signature, could be PKCS1, PKCS7 and PKCS7Detached. |

## See Also

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, System::String, System::String, System::String, bool, System::Drawing::Rectangle) method


Make a signature on the pdf document.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, System::String SigReason, System::String SigContact, System::String SigLocation, bool visible, System::Drawing::Rectangle annotRect)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The page number on which signature is made. |
| SigReason | System::String | The reason of signature. |
| SigContact | System::String | The contact of signature. |
| SigLocation | System::String | The location of signature. |
| visible | bool | The visiblity of signature. |
| annotRect | System::Drawing::Rectangle | The rect of signature. |

## See Also

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, System::String, System::String, System::String, bool, System::Drawing::Rectangle, System::SharedPtr\<Forms::Signature\>) method


Sign the document with the given type signature.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, System::String SigReason, System::String SigContact, System::String SigLocation, bool visible, System::Drawing::Rectangle annotRect, System::SharedPtr<Forms::Signature> sig)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The page number on which signature is made. |
| SigReason | System::String | The reason of signature. |
| SigContact | System::String | The contact of signature. |
| SigLocation | System::String | The location of signature. |
| visible | bool | The visiblity of signature. |
| annotRect | System::Drawing::Rectangle | The rect of signature. |
| sig | System::SharedPtr\<Forms::Signature\> | The type of the signature, could be PKCS1, PKCS7 and PKCS7Detached. |

## See Also

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(System::String, System::SharedPtr\<Forms::Signature\>) method


Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(System::String SigName, System::SharedPtr<Forms::Signature> sig)
```


| Parameter | Type | Description |
| --- | --- | --- |
| SigName | System::String | The name of the signature field. |
| sig | System::SharedPtr\<Forms::Signature\> | The type of the signature, could be PKCS1 (Pkcs1Signature object), PKCS7 and PKCS7 detached (Pkcs7Signature object) |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(System::String, System::String, System::String, System::String, System::SharedPtr\<Forms::Signature\>) method


Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(System::String SigName, System::String SigReason, System::String SigContact, System::String SigLocation, System::SharedPtr<Forms::Signature> sig)
```


| Parameter | Type | Description |
| --- | --- | --- |
| SigName | System::String | The name of the signature field. |
| SigReason | System::String | The reason of signature. |
| SigContact | System::String | The contact of signature. |
| SigLocation | System::String | The location of signature. |
| sig | System::SharedPtr\<Forms::Signature\> | The type of the signature, could be PKCS1, PKCS7 and PKCS7Detached. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
