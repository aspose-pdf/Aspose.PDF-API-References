---
title: "System::Security::Cryptography::RSA::Decrypt método"
linktitle: "Decrypt"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSA::Decrypt método. Descifra los datos de entrada usando el modo de relleno especificado en C++."
type: docs
weight: 100
url: /es/cpp/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt method


Descifra los datos de entrada usando el modo de relleno especificado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
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
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
