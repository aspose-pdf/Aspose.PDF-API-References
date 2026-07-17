---
title: Aspose::Pdf::Forms::SignatureField::Sign method
linktitle: Sign
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::SignatureField::Sign method. Sign the document using this signature field in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.forms/signaturefield/sign/
---
## SignatureField::Sign(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&) method


Sign the document using this signature field.

```cpp
void Aspose::Pdf::Forms::SignatureField::Sign(const System::SharedPtr<Aspose::Pdf::Forms::Signature> &signature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signature | const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\& | [Signature](../../signature/) object, see [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/) and [PKCS7Detached](../../pkcs7detached/). |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../signature/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## SignatureField::Sign(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Signs the document using this signature field.

```cpp
void Aspose::Pdf::Forms::SignatureField::Sign(const System::SharedPtr<Aspose::Pdf::Forms::Signature> &signature, const System::SharedPtr<System::IO::Stream> &pfx, const System::String &pass)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signature | const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\& | [Signature](../../signature/) object, see [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/), [PKCS7Detached](../../pkcs7detached/). |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Stream with certificate. |
| pass | const System::String\& | Password to access private in the *pfx* . |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../signature/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
