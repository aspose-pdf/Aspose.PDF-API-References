---
title: "Aspose::Pdf::Forms::SignatureField::Sign metod"
linktitle: "Signera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::SignatureField::Sign metod. Signera dokumentet med detta signaturfält i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.forms/signaturefield/sign/
---
## SignatureField::Sign(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&) method


Signera dokumentet med detta signaturfält.

```cpp
void Aspose::Pdf::Forms::SignatureField::Sign(const System::SharedPtr<Aspose::Pdf::Forms::Signature> &signature)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signature | const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\& | [Signature](../../signature/) objekt, se [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/) och [PKCS7Detached](../../pkcs7detached/). |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../signature/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## SignatureField::Sign(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Signerar dokumentet med detta signaturfält.

```cpp
void Aspose::Pdf::Forms::SignatureField::Sign(const System::SharedPtr<Aspose::Pdf::Forms::Signature> &signature, const System::SharedPtr<System::IO::Stream> &pfx, const System::String &pass)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signature | const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\& | [Signature](../../signature/) objekt, se [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/), [PKCS7Detached](../../pkcs7detached/). |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Ström med certifikat. |
| pass | const System::String\& | Lösenord för att komma åt privat i *pfx*. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../signature/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
