---
title: "Aspose::Pdf::Forms::Signature::Verify método"
linktitle: "Verify"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::Signature::Verify método. Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario en C++."
type: docs
weight: 3100
url: /es/cpp/aspose.pdf.forms/signature/verify/
---
## Signature::Verify() method


Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify()
```


### ReturnValue

true si el documento es válido.

## Ver también

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Verify(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify(const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| opciones | const System::SharedPtr\<Security::ValidationOptions\>\& | Las opciones de verificación. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | El resultado de la validación del certificado. |

### ReturnValue

true si el documento es válido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::Verify(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Verifica el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. La verificación se realiza utilizando el certificado de clave pública externo.

```cpp
bool Aspose::Pdf::Forms::Signature::Verify(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado de clave pública para la verificación. |
| opciones | const System::SharedPtr\<Security::ValidationOptions\>\& | Las opciones de verificación. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | El resultado de la validación del certificado. |

### ReturnValue

true si el documento es válido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
