---
title: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash método"
linktitle: "VerifyHash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash método. Comprueba la firma de los datos en C++."
type: docs
weight: 1800
url: /es/cpp/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash method


Comprueba la firma de los datos.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
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
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
