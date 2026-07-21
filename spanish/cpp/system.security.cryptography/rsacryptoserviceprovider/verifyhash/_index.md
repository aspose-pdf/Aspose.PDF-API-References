---
title: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash método"
linktitle: "VerifyHash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash método. Verifica que la firma del hash especificado sea válida en C++."
type: docs
weight: 1900
url: /es/cpp/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method


Verifica que la firma del hash especificado sea válida.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | ByteArrayPtr | Valor hash de los datos firmados. |
| firma | ByteArrayPtr | Datos de la firma. |
| hash_algorithm | const HashAlgorithmName\& | Algoritmo de hash. |
| relleno | SharedPtr\<RSASignaturePadding\> | Modo de relleno. devuelve true si la firma es válida, de lo contrario - false. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method


Comprueba la firma de los datos.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Hash calculado para los datos recibidos. |
| str | const String\& | Nombre del algoritmo hash utilizado. |
| rgb_signature | const ByteArrayPtr\& | Firma tal como se recibió. |

### ReturnValue

Verdadero si la firma es válida, falso en caso contrario.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
