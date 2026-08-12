---
title: "Clase System::Security::Cryptography::X509Certificates::PublicKey"
linktitle: "PublicKey"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::X509Certificates::PublicKey. Representa la información de la clave pública de un certificado X509. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.security.cryptography.x509certificates/publickey/
---
## PublicKey class


Representa la información de la clave pública de un certificado X509. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class PublicKey : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_EncodedKeyValue](./get_encodedkeyvalue/)() const | Obtiene el valor de la clave pública codificado en ASN.1. |
| [get_EncodedParameters](./get_encodedparameters/)() const | Obtiene los parámetros de la clave pública codificados en ASN.1. |
| [get_Key](./get_key/)() const | Obtiene un [RSACryptoServiceProvider](../../system.security.cryptography/rsacryptoserviceprovider/) o [DSACryptoServiceProvider](../../system.security.cryptography/dsacryptoserviceprovider/). |
| [get_Oid](./get_oid/)() const | Obtiene el identificador (OID) de la clave pública. |
| [PublicKey](./publickey/)(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) | Constructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
