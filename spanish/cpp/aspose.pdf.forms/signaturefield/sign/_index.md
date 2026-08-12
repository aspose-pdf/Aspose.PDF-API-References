---
title: "Aspose::Pdf::Forms::SignatureField::Sign method"
linktitle: "Firmar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::SignatureField::Sign method. Firma el documento usando este campo de firma en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.forms/signaturefield/sign/
---
## SignatureField::Sign(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&) method


Firma el documento usando este campo de firma.

```cpp
void Aspose::Pdf::Forms::SignatureField::Sign(const System::SharedPtr<Aspose::Pdf::Forms::Signature> &signature)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signature | const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\& | Objeto [Signature](../../signature/), vea [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/) y [PKCS7Detached](../../pkcs7detached/). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../signature/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## SignatureField::Sign(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Firma el documento usando este campo de firma.

```cpp
void Aspose::Pdf::Forms::SignatureField::Sign(const System::SharedPtr<Aspose::Pdf::Forms::Signature> &signature, const System::SharedPtr<System::IO::Stream> &pfx, const System::String &pass)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signature | const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\& | Objeto [Signature](../../signature/), vea [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/), [PKCS7Detached](../../pkcs7detached/). |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con certificado. |
| pasar | const System::String\& | Contraseña para acceder a la clave privada en el *pfx*. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../signature/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
