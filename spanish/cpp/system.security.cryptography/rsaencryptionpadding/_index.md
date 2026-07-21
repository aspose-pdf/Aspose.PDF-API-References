---
title: "System::Security::Cryptography::RSAEncryptionPadding clase"
linktitle: "RSAEncryptionPadding"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSAEncryptionPadding clase. Modo de relleno y parámetros para operaciones de cifrado o descifrado RSA en C++."
type: docs
weight: 3600
url: /es/cpp/system.security.cryptography/rsaencryptionpadding/
---
## RSAEncryptionPadding class


Modo de relleno y parámetros para el cifrado o descifrado [RSA](../rsa/).

```cpp
class RSAEncryptionPadding : public System::IEquatable<SharedPtr<RSAEncryptionPadding>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [CreateOaep](./createoaep/)(const HashAlgorithmName\&) | Crea [RSAEncryptionPadding](./) con modo OAEP y algoritmo hash especificado. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(SharedPtr\<RSAEncryptionPadding\>) override |  |
| [get_Mode](./get_mode/)() const | Obtiene el modo de relleno. |
| [get_OaepHashAlgorithm](./get_oaephashalgorithm/)() const | Obtiene el algoritmo hash usado con OAEP. |
| static [get_OaepSHA1](./get_oaepsha1/)() | Obtiene el modo OAEP con algoritmo hash [SHA1](../sha1/). |
| static [get_OaepSHA256](./get_oaepsha256/)() | Obtiene el modo OAEP con algoritmo hash [SHA256](../sha256/). |
| static [get_OaepSHA384](./get_oaepsha384/)() | Obtiene el modo OAEP con algoritmo hash [SHA384](../sha384/). |
| static [get_OaepSHA512](./get_oaepsha512/)() | Obtiene el modo OAEP con algoritmo hash [SHA512](../sha512/). |
| static [get_Pkcs1](./get_pkcs1/)() | Información RTTI. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
## Ver también

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
