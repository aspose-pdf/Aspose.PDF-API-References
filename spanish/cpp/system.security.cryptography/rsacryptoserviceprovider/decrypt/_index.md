---
title: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt método"
linktitle: "Decrypt"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt método. Descifra los datos de entrada usando el modo de relleno especificado en C++."
type: docs
weight: 200
url: /es/cpp/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Descifra los datos de entrada usando el modo de relleno especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | ByteArrayPtr | Matriz de [Byte](../../../system/byte/) para descifrar. |
| relleno | SharedPtr\<RSAEncryptionPadding\> | Modo de relleno. |

### ReturnValue

Datos descifrados en formato de matriz de bytes.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method


Descifra mensaje. No implementado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Data](../../../system.data/) para descifrar. |
| use_oaep | bool | True para usar relleno OAEP, false para usar relleno PKCS#1 v1.5. |

### ReturnValue

Matriz de datos descifrada.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
