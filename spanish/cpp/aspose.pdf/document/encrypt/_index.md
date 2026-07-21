---
title: "Aspose::Pdf::Document::Encrypt método"
linktitle: "Cifrar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Document::Encrypt method. Encripta el documento en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf/document/encrypt/
---
## Document::Encrypt(Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>\&) method


Encripta el documento.

```cpp
void Aspose::Pdf::Document::Encrypt(Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, const System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2>>> &publicCertificates)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| permissions | Aspose::Pdf::Permissions | [Document](../) permisos, vea [Permisos](../../permissions/) para más detalles. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Algoritmo criptográfico, vea [CryptoAlgorithm](../../cryptoalgorithm/) para más detalles. |
| publicCertificates | const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>\& | Los certificados públicos utilizados para el cifrado — uno por destinatario. |
## Observaciones



Este método prepara el cifrado. Para encriptar un documento, necesita llamar al método Save para guardarlo.
## Ver también

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) method


Encripta el documento.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | const System::String\& | Contraseña de usuario. |
| ownerPassword | const System::String\& | Contraseña del propietario. |
| permissions | Aspose::Pdf::Permissions | [Document](../) permisos, vea [Permisos](../../permissions/) para más detalles. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Algoritmo criptográfico, vea [CryptoAlgorithm](../../cryptoalgorithm/) para más detalles. |
## Observaciones



Este método prepara el cifrado. Para encriptar un documento, necesita llamar al método Save para guardarlo.
## Ver también

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) method


Encripta el documento.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, Aspose::Pdf::Permissions permissions, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | const System::String\& | Contraseña de usuario. |
| ownerPassword | const System::String\& | Contraseña del propietario. |
| permissions | Aspose::Pdf::Permissions | [Document](../) permisos, vea [Permisos](../../permissions/) para más detalles. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Algoritmo criptográfico, vea [CryptoAlgorithm](../../cryptoalgorithm/) para más detalles. |
| usePdf20 | bool | Compatibilidad con la revisión 6 (Extensión 8). |
## Observaciones



Este método prepara el cifrado. Para encriptar un documento, necesita llamar al método Save para guardarlo.
## Ver también

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) method


Encripta el documento.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, Aspose::Pdf::Permissions permissions, const System::SharedPtr<Security::ICustomSecurityHandler> &customHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | const System::String\& | Contraseña de usuario. |
| ownerPassword | const System::String\& | Contraseña del propietario. |
| permissions | Aspose::Pdf::Permissions | [Document](../) permisos, vea [Permisos](../../permissions/) para más detalles. |
| customHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | El controlador de seguridad personalizado. |
## Observaciones



Este método prepara el cifrado. Para encriptar un documento, necesita llamar al método Save para guardarlo.
## Ver también

* Class [String](../../../system/string/)
* Enum [Permissions](../../permissions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, Aspose::Pdf::CryptoAlgorithm, bool) method


Encripta el documento.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<Facades::DocumentPrivilege> &privileges, Aspose::Pdf::CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | const System::String\& | Contraseña de usuario. |
| ownerPassword | const System::String\& | Contraseña del propietario. |
| privileges | const System::SharedPtr\<Facades::DocumentPrivilege\>\& | [Document](../) permisos, vea [Permisos](../../permissions/) para más detalles. |
| cryptoAlgorithm | Aspose::Pdf::CryptoAlgorithm | Algoritmo criptográfico, vea [CryptoAlgorithm](../../cryptoalgorithm/) para más detalles. |
| usePdf20 | bool | Compatibilidad con la revisión 6 (Extensión 8). |
## Observaciones



Este método prepara el cifrado. Para encriptar un documento, necesita llamar al método Save para guardarlo.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Encrypt(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) method


Encripta el documento.

```cpp
void Aspose::Pdf::Document::Encrypt(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<Facades::DocumentPrivilege> &privileges, const System::SharedPtr<Security::ICustomSecurityHandler> &customHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | const System::String\& | Contraseña de usuario. |
| ownerPassword | const System::String\& | Contraseña del propietario. |
| privileges | const System::SharedPtr\<Facades::DocumentPrivilege\>\& | [Document](../) permisos, vea [Permisos](../../permissions/) para más detalles. |
| customHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | El controlador de seguridad personalizado. |
## Observaciones



Este método prepara el cifrado. Para encriptar un documento, necesita llamar al método Save para guardarlo.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
