---
title: "System::Security::Cryptography::DSACryptoServiceProvider::SignHash method"
linktitle: "SignHash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider::SignHash method. Calcula la firma del valor de entrada especificado en C++."
type: docs
weight: 1600
url: /es/cpp/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash method


Calcula la firma del valor de entrada especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Valor hash de los datos a firmar. |
| str | const String\& | Identificador del algoritmo de hash usado para crear el hash. |

### ReturnValue

[DSA](../../dsa/) signature for specified data.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
