---
title: "Aspose::Pdf::Forms::Signature::TryVerify método"
linktitle: "TryVerify"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::Signature::TryVerify método. Intenta verificar el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario en C++."
type: docs
weight: 3000
url: /es/cpp/aspose.pdf.forms/signature/tryverify/
---
## Signature::TryVerify(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Intenta verificar el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| opciones | const System::SharedPtr\<Security::ValidationOptions\>\& | Las opciones de verificación. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | El resultado de la validación del certificado. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | El resultado de la verificación. |

### ReturnValue

Devuelve true si la firma se procesó correctamente. Devuelve false si ocurrió un error durante el proceso de verificación o si la firma estaba corrupta o comprometida.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::TryVerify(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Intenta verificar el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario. La verificación se realiza utilizando el certificado de clave pública externo.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado de clave pública para la verificación. |
| opciones | const System::SharedPtr\<Security::ValidationOptions\>\& | Las opciones de verificación. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | El resultado de la validación del certificado. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | El resultado de la verificación. |

### ReturnValue

Devuelve true si la firma se procesó correctamente. Devuelve false si ocurrió un error durante el proceso de verificación o si la firma estaba corrupta o comprometida.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Signature::TryVerify(System::SharedPtr\<Security::VerificationResult\>\&) method


Intenta verificar el documento respecto a esta firma y devuelve true si el documento es válido o false en caso contrario.

```cpp
bool Aspose::Pdf::Forms::Signature::TryVerify(System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | El resultado de la verificación. |

### ReturnValue

Devuelve true si la firma se procesó correctamente. Devuelve false si ocurrió un error durante el proceso de verificación o si la firma estaba corrupta o comprometida.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
