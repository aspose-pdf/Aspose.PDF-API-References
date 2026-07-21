---
title: "Método System::Security::Cryptography::RSACryptoServiceProvider::VerifyData"
linktitle: "VerifyData"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Security::Cryptography::RSACryptoServiceProvider::VerifyData. Verifica la firma de los datos en C++."
type: docs
weight: 1800
url: /es/cpp/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData method


Comprueba la firma de los datos.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Data](../../../system.data/) para verificar la firma. |
| halg | const SharedPtr\<Object\>\& | Algoritmo hash a usar. |
| firma | const ByteArrayPtr\& | Firma tal como se recibió. |

### ReturnValue

Verdadero si la firma es válida, falso en caso contrario.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
