---
title: "Constructor de Aspose::Pdf::Forms::ExternalSignature::ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor de Aspose::Pdf::Forms::ExternalSignature::ExternalSignature. Crea una firma PKCS#7 (desprendida) usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature::ExternalSignature(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) constructor


Crea una firma PKCS#7 **(detached)** separada usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| certificado | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado con la clave privada. |
## Observaciones



El algoritmo de resumen se seleccionará automáticamente en función de los datos de la clave del certificado.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, bool) constructor


Crea una firma PKCS#7 separada usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate, bool detached)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| certificado | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado con la clave privada. |
| desprendido | bool | Verdadero si la firma debe ser desprendida, de lo contrario falso. |
## Observaciones



Para detached configurado como false, el algoritmo de resumen será siempre **SHA1**. De lo contrario, el algoritmo de resumen se seleccionará automáticamente en función de los datos de la clave del certificado (ver [DigestHashAlgorithm::Auto](../../../aspose.pdf/digesthashalgorithm/) ).
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, DigestHashAlgorithm) constructor


Crea una firma PKCS#7 **(detached)** separada usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> &certificate, DigestHashAlgorithm digestHashAlgorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| certificado | const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\& | El certificado con la clave privada. |
| digestHashAlgorithm | DigestHashAlgorithm | El algoritmo de resumen para firmar un documento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::String\&, bool) constructor


Crea una firma PKCS#7 usando un X509Certificate2 como cadena base64.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::String &base64, bool detached)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| base64 | const System::String\& | X509Certificate2 como cadena base64. |
| desprendido | bool | Verdadero si la firma debe ser desprendida, de lo contrario falso. |
## Observaciones



Para detached configurado como false, el algoritmo de resumen será siempre **SHA1**. De lo contrario, el algoritmo de resumen se seleccionará automáticamente en función de los datos de la clave del certificado (ver [DigestHashAlgorithm::Auto](../../../aspose.pdf/digesthashalgorithm/) ).
## Ver también

* Class [String](../../../system/string/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## ExternalSignature::ExternalSignature(const System::String\&, DigestHashAlgorithm) constructor


Crea una firma PKCS#7 **(detached)** separada usando un X509Certificate2 como cadena base64.

```cpp
Aspose::Pdf::Forms::ExternalSignature::ExternalSignature(const System::String &base64, DigestHashAlgorithm digestHashAlgorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| base64 | const System::String\& | X509Certificate2 como cadena base64. |
| digestHashAlgorithm | DigestHashAlgorithm | El algoritmo de resumen para firmar un documento. |

## Ver también

* Class [String](../../../system/string/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [ExternalSignature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
