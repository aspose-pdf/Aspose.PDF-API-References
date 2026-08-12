---
title: "System::Security::Cryptography::RSA::Encrypt método"
linktitle: "Cifrar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSA::Encrypt método. Cifra los datos de entrada usando el modo de relleno especificado en C++."
type: docs
weight: 300
url: /es/cpp/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt method


Cifra los datos de entrada usando el modo de relleno especificado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
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
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
