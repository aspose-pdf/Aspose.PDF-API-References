---
title: "System::Security::Cryptography::RSA::SignHash método"
linktitle: "SignHash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSA::SignHash método. Calcula la firma para el valor hash especificado en C++."
type: docs
weight: 1100
url: /es/cpp/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash method


Calcula la firma para el valor hash especificado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | ByteArrayPtr | Valor hash. |
| hash_algorithm | HashAlgorithmName | Algoritmo de hash. |
| padding | SharedPtr\<RSASignaturePadding\> | Modo de relleno. devuelve la firma [RSA](../) para el hash especificado. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
