---
title: "System::Security::Cryptography::RSACryptoServiceProvider::Encrypt método"
linktitle: "Cifrar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::Encrypt método. Cifra los datos de entrada usando el modo de relleno especificado en C++."
type: docs
weight: 400
url: /es/cpp/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Cifra los datos de entrada usando el modo de relleno especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | ByteArrayPtr | Matriz de [Byte](../../../system/byte/) para cifrar. |
| relleno | SharedPtr\<RSAEncryptionPadding\> | Modo de relleno. |

### ReturnValue

Datos cifrados en formato de matriz de bytes.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) method


Encripta mensaje. No implementado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Data](../../../system.data/) para cifrar. |
| use_oaep | bool | True para usar relleno OAEP, false para usar relleno PKCS#1 v1.5. |

### ReturnValue

Matriz de datos cifrada.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
