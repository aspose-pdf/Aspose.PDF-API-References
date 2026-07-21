---
title: "Clase System::Security::Cryptography::X509Certificates::X509Certificate2"
linktitle: "X509Certificate2"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::X509Certificates::X509Certificate2. Representa un certificado X509. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 class


Representa un certificado X509. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Archived](./get_archived/)() const | Obtiene un valor que indica que el certificado está archivado. |
| [get_Extensions](./get_extensions/)() const | Obtiene la colección de objetos de extensión asociados al certificado. |
| [get_FriendlyName](./get_friendlyname/)() const | Obtiene el nombre descriptivo del certificado. |
| [get_HasPrivateKey](./get_hasprivatekey/)() const | Comprueba si el certificado tiene clave privada. |
| [get_IssuerName](./get_issuername/)() const | Obtiene el nombre de la entidad que emitió el certificado. |
| [get_NotAfter](./get_notafter/)() const | Obtiene la fecha y hora locales después de las cuales el certificado ya no es válido. |
| [get_NotBefore](./get_notbefore/)() const | Obtiene la fecha y hora locales en las que el certificado se vuelve válido. |
| [get_PrivateKey](./get_privatekey/)() const | Obtiene la clave privada asociada al certificado. |
| [get_PublicKey](./get_publickey/)() const | Obtiene un objeto [PublicKey](../publickey/) de certificado. |
| [get_RawData](./get_rawdata/)() const | Obtiene los datos sin procesar del certificado. |
| [get_SerialNumber](./get_serialnumber/)() const | Obtiene el número de serie de un certificado. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Obtiene el algoritmo usado para crear la firma de un certificado. |
| [get_SubjectName](./get_subjectname/)() const | Obtiene el nombre del sujeto de un certificado. |
| [get_Thumbprint](./get_thumbprint/)() const | Obtiene la huella digital del certificado. |
| [get_Version](./get_version/)() const | Obtiene la versión del formato del certificado. |
| static [GetCertContentType](./getcertcontenttype/)(const ByteArrayPtr\&) | Obtiene el tipo de certificado contenido en la matriz de bytes especificada. |
| static [GetCertContentType](./getcertcontenttype/)(const String\&) | Obtiene el tipo de certificado contenido en el archivo especificado. |
| [GetDSAPrivateKey](./getdsaprivatekey/)() const | Obtiene la clave privada [RSA](../../system.security.cryptography/rsa/). |
| [GetDSAPublicKey](./getdsapublickey/)() const | Obtiene la clave pública [RSA](../../system.security.cryptography/rsa/). |
| [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Obtiene la clave privada [RSA](../../system.security.cryptography/rsa/). |
| [GetECDsaPublicKey](./getecdsapublickey/)() const | Obtiene la clave pública [RSA](../../system.security.cryptography/rsa/). |
| [GetNameInfo](./getnameinfo/)(X509NameType, bool) const | Obtiene el nombre del sujeto o del emisor del certificado. |
| [GetRSAPrivateKey](./getrsaprivatekey/)() const | Obtiene la clave privada [RSA](../../system.security.cryptography/rsa/). |
| [GetRSAPublicKey](./getrsapublickey/)() const | Obtiene la clave pública [RSA](../../system.security.cryptography/rsa/). |
| [Import](./import/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Importa información del archivo de certificado especificado. |
| [Import](./import/)(const String\&, const String\&, X509KeyStorageFlags) override | Importa información del archivo de certificado especificado. |
| [Import](./import/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Importa información de los datos de certificado especificados. |
| [Import](./import/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) override | Importa información de los datos de certificado especificados. |
| [Import](./import/)(const String\&) override | Importa información del archivo de certificado especificado. |
| [Import](./import/)(const ByteArrayPtr\&) override | Importa información de los datos de certificado especificados. |
| [Reset](./reset/)() override | Restablece el estado del certificado. |
| [set_Archived](./set_archived/)(bool) const | Establece un valor que indica que el certificado está archivado. |
| [set_FriendlyName](./set_friendlyname/)(const String\&) | Establece el nombre descriptivo del certificado. |
| [set_PrivateKey](./set_privatekey/)(const SharedPtr\<AsymmetricAlgorithm\>\&) | Establece o elimina la clave privada asociada al certificado. |
| [ToString](./tostring/)(bool) const override | Devuelve la información del certificado en formato de texto. |
| [ToString](./tostring/)() const override | Devuelve la información del certificado en formato de texto. |
| [Verify](./verify/)() const | Verifica la cadena de certificados. |
| [X509Certificate2](./x509certificate2/)() | Construye un [X509Certificate2](./) vacío. |
| [X509Certificate2](./x509certificate2/)(const String\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const SharedPtr\<X509Certificate\>\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) | Constructor. |
## Ver también

* Class [X509Certificate](../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
