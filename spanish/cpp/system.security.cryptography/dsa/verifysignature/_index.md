---
title: "System::Security::Cryptography::DSA::VerifySignature método"
linktitle: "VerifySignature"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::DSA::VerifySignature método. Verifica la firma DSA para los datos especificados en C++."
type: docs
weight: 800
url: /es/cpp/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature method


Verificar firma [DSA](../) para los datos especificados.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb_hash | ByteArrayPtr | [Data](../../../system.data/) firmada con **rgb_signature**. |
| rgb_signature | ByteArrayPtr | Firma [DSA](../). |

### ReturnValue

true - si **rgb_signature** coincide con la firma [DSA](../) calculada sobre **rgb_hash**, de lo contrario - false.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
