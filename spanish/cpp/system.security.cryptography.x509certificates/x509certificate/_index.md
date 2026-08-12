---
title: "System::Security::Cryptography::X509Certificates::X509Certificate clase"
linktitle: "X509Certificate"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::X509Certificates::X509Certificate clase. Certificado X.509 v.3. No se admiten certificados cifrados. Solo se admite la bandera X509KeyStorageFlags::DefaultKeySet. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate class


Certificado X.509 v.3. No se admiten certificados cifrados. Solo se admite la bandera [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [CreateFromCertFile](./createfromcertfile/)(const String\&) | Crea un certificado a partir del archivo PKCS7 especificado. |
| static [CreateFromSignedFile](./createfromsignedfile/)(const String\&) | Crea un certificado a partir del archivo firmado especificado. |
| [Dispose](./dispose/)() override | No hace nada. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compara dos certificados. |
| virtual [Export](./export/)(X509ContentType) const | Exporta el objeto actual a una matriz de bytes usando el formato especificado. NO IMPLEMENTADO. |
| virtual [Export](./export/)(X509ContentType, const SecureStringPtr\&) const | Exporta el objeto actual a una matriz de bytes usando el formato especificado. NO IMPLEMENTADO. |
| virtual [Export](./export/)(X509ContentType, const String\&) const | Exporta el objeto actual a una matriz de bytes usando el formato especificado. NO IMPLEMENTADO. |
| [get_Handle](./get_handle/)() const | Obtiene un manejador al contexto de certificado de la API criptográfica de Microsoft. |
| [get_Issuer](./get_issuer/)() const | Obtiene el nombre de la autoridad certificadora que emitió el certificado X.509v3. |
| [get_Subject](./get_subject/)() const | Obtiene el nombre distinguido del sujeto del certificado. |
| virtual [GetCertHash](./getcerthash/)() const | Obtiene el hash del objeto actual como una matriz de bytes. |
| virtual [GetCertHash](./getcerthash/)(const HashAlgorithmName\&) const | Obtiene el hash del objeto actual como una matriz de bytes. |
| virtual [GetCertHashString](./getcerthashstring/)() const | Obtiene el hash [SHA1](../../system.security.cryptography/sha1/) del objeto actual como una cadena hexadecimal. |
| virtual [GetCertHashString](./getcerthashstring/)(const HashAlgorithmName\&) const | Obtiene el hash [SHA1](../../system.security.cryptography/sha1/) del objeto actual como una cadena hexadecimal. |
| virtual [GetEffectiveDateString](./geteffectivedatestring/)() const | Obtiene la fecha de vigencia del certificado actual. |
| virtual [GetExpirationDateString](./getexpirationdatestring/)() const | Obtiene la fecha de expiración del certificado actual. |
| virtual [GetFormat](./getformat/)() const | Obtiene el nombre del formato del certificado. |
| [GetHashCode](./gethashcode/)() const override | Obtiene el código hash del certificado. |
| virtual [GetIssuerName](./getissuername/)() const | Obtiene el nombre de la autoridad certificadora que emitió el certificado actual. |
| virtual [GetKeyAlgorithm](./getkeyalgorithm/)() const | Obtiene información clave del certificado actual como una cadena. |
| virtual [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | Obtiene información clave del certificado actual como una matriz de bytes. |
| virtual [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | Obtiene información clave del certificado actual como una cadena hexadecimal. |
| virtual [GetName](./getname/)() const | Obtiene el nombre del principal al que se emitió el certificado actual. |
| virtual [GetPublicKey](./getpublickey/)() const | Obtiene la clave pública del certificado como una matriz de bytes. |
| virtual [GetPublicKeyString](./getpublickeystring/)() const | Obtiene la clave pública del certificado como una cadena hexadecimal. |
| virtual [GetRawCertData](./getrawcertdata/)() const | Obtiene los datos sin procesar del certificado como una matriz de bytes. |
| virtual [GetRawCertDataString](./getrawcertdatastring/)() const | Obtiene los datos sin procesar del certificado como una cadena hexadecimal. |
| virtual [GetSerialNumber](./getserialnumber/)() const | Obtiene el número de serie del certificado como una matriz de bytes. |
| virtual [GetSerialNumberString](./getserialnumberstring/)() const | Obtiene el número de serie del certificado como una cadena hexadecimal. |
| virtual [Import](./import/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Importa información del archivo de certificado especificado. NO IMPLEMENTADO. |
| virtual [Import](./import/)(const String\&, const String\&, X509KeyStorageFlags) | Importa información del archivo de certificado especificado. NO IMPLEMENTADO. |
| virtual [Import](./import/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Importa información de los datos de certificado especificados. NO IMPLEMENTADO. |
| virtual [Import](./import/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Importa información de los datos de certificado especificados. NO IMPLEMENTADO. |
| virtual [Import](./import/)(const String\&) | Importa información del archivo de certificado especificado. NO IMPLEMENTADO. |
| virtual [Import](./import/)(const ByteArrayPtr\&) | Importa información de los datos de certificado especificados. NO IMPLEMENTADO. |
| [operator=](./operator=/)(const X509Certificate\&) |  |
| virtual [Reset](./reset/)() | Restablece el estado del certificado. |
| virtual [ToString](./tostring/)(bool) const | Devuelve la información del certificado en formato de texto. |
| [ToString](./tostring/)() const override | Devuelve la información del certificado en formato de texto. |
| [X509Certificate](./x509certificate/)(const X509Certificate\&) |  |
| [X509Certificate](./x509certificate/)() | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const SharedPtr\<X509Certificate\>\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const String\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const SecureStringPtr\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&, const String\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&, const SecureStringPtr\&) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&, const String\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate](./x509certificate/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Constructor. |
| [X509Certificate](./x509certificate/)(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) | Constructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Tipo de puntero. |
## Ver también

* Class [Object](../../system/object/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
