---
title: "Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature método"
linktitle: "TryVerifySignature"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature método. Intente comprobar la validez de una firma en C++."
type: docs
weight: 3800
url: /es/cpp/aspose.pdf.facades/pdffilesignature/tryverifysignature/
---
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Intenta verificar la validez de una firma.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |
| opciones | const System::SharedPtr\<Security::ValidationOptions\>\& | Las opciones de verificación. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | El resultado de la validación del certificado. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | El resultado de la verificación. |

### ReturnValue

Devuelve **true** si la firma se procesó correctamente. Devuelve **false** si ocurrió un error durante el proceso de verificación o la firma estaba corrupta o comprometida.
## Observaciones



Este método le permite comprobar el certificado de firma usando OCSP y/o CRL (lista de revocación de certificados) para revocación. Este método no verifica la cadena de certificados ni su validez, pero sí comprueba si el certificado final ha sido revocado.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Intenta verificar la validez de una firma. La verificación se realiza utilizando el certificado de clave pública externo.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado de clave pública para la verificación. |
| opciones | const System::SharedPtr\<Security::ValidationOptions\>\& | Las opciones de verificación. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | El resultado de la validación del certificado. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | El resultado de la verificación. |

### ReturnValue

Devuelve **true** si la firma se procesó correctamente. Devuelve **false** si ocurrió un error durante el proceso de verificación o la firma estaba corrupta o comprometida.
## Observaciones



Este método le permite comprobar el certificado de firma usando OCSP y/o CRL (lista de revocación de certificados) para revocación. Este método no verifica la cadena de certificados ni su validez, pero sí comprueba si el certificado final ha sido revocado.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Intenta verificar la validez de una firma. La verificación se realiza utilizando el certificado de clave pública externo.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado de clave pública para la verificación. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | El resultado de la verificación. |

### ReturnValue

Devuelve **true** si la firma se procesó correctamente. Devuelve **false** si ocurrió un error durante el proceso de verificación o la firma estaba corrupta o comprometida.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::TryVerifySignature(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<Security::VerificationResult\>\&) method


Intenta verificar la validez de una firma.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::TryVerifySignature(const System::SharedPtr<SignatureName> &signName, System::SharedPtr<Security::VerificationResult> &verificationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |
| verificationResult | System::SharedPtr\<Security::VerificationResult\>\& | El resultado de la verificación. |

### ReturnValue

Devuelve **true** si la firma se procesó correctamente. Devuelve **false** si ocurrió un error durante el proceso de verificación o la firma estaba corrupta o comprometida.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [VerificationResult](../../../aspose.pdf.security/verificationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
