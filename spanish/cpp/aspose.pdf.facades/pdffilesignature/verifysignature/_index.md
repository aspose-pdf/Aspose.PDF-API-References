---
title: "Aspose::Pdf::Facades::PdfFileSignature::VerifySignature método"
linktitle: "VerifySignature"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::VerifySignature método. Comprueba la validez de una firma en C++."
type: docs
weight: 3900
url: /es/cpp/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&) method


Comprueba la validez de una firma.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |

### ReturnValue

Devuelve un resultado de tipo bool.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Comprueba la validez de una firma.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |
| opciones | const System::SharedPtr\<Security::ValidationOptions\>\& | Las opciones de verificación. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | El resultado de la validación del certificado. |

### ReturnValue

Devuelve un resultado de tipo bool.
## Observaciones



Este método le permite comprobar el certificado de firma usando OCSP y/o CRL (lista de revocación de certificados) para revocación. Este método no verifica la cadena de certificados ni su validez, pero sí comprueba si el certificado final ha sido revocado.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) method


Comprueba la validez de una firma. La verificación se realiza utilizando el certificado de clave pública externo.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado de clave pública para la verificación. |

### ReturnValue

Devuelve un resultado de tipo bool.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Comprueba la validez de una firma. La verificación se realiza utilizando el certificado de clave pública externo.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::SharedPtr<SignatureName> &signName, const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &publicKeyCertificate, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |
| publicKeyCertificate | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado de clave pública para la verificación. |
| opciones | const System::SharedPtr\<Security::ValidationOptions\>\& | Las opciones de verificación. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | El resultado de la validación del certificado. |

### ReturnValue

Devuelve un resultado de tipo bool.
## Observaciones



Este método le permite comprobar el certificado de firma usando OCSP y/o CRL (lista de revocación de certificados) para revocación. Este método no verifica la cadena de certificados ni su validez, pero sí comprueba si el certificado final ha sido revocado.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SignatureName](../../signaturename/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::String\&) method


Comprueba la validez de una firma.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::String &signName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::String\& | El nombre de la firma. |

### ReturnValue

Devuelve un resultado de tipo bool.

## Deprecated
Use el método VerifySignature(SignatureName) en su lugar.

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::VerifySignature(const System::String\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) method


Comprueba la validez de una firma.

```cpp
bool Aspose::Pdf::Facades::PdfFileSignature::VerifySignature(const System::String &signName, const System::SharedPtr<Security::ValidationOptions> &options, System::SharedPtr<Security::ValidationResult> &validationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::String\& | El nombre de la firma. |
| opciones | const System::SharedPtr\<Security::ValidationOptions\>\& | Las opciones de verificación. |
| validationResult | System::SharedPtr\<Security::ValidationResult\>\& | El resultado de la validación del certificado. |

### ReturnValue

Devuelve un resultado de tipo bool.
## Observaciones


## Deprecated
Use el método VerifySignature(SignatureName, ValidationOptions, out ValidationResult) en su lugar.


Este método le permite comprobar el certificado de firma usando OCSP y/o CRL (lista de revocación de certificados) para revocación. Este método no verifica la cadena de certificados ni su validez, pero sí comprueba si el certificado final ha sido revocado.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
