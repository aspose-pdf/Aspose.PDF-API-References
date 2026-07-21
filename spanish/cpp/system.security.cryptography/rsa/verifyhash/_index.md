---
title: "System::Security::Cryptography::RSA::VerifyHash método"
linktitle: "VerifyHash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSA::VerifyHash método. Verifica que la firma del hash especificado sea válida en C++."
type: docs
weight: 1400
url: /es/cpp/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash method


Verifica que la firma del hash especificado sea válida.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
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
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
