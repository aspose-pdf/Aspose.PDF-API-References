---
title: "System::Net::Security::EncryptionPolicy enumeración"
linktitle: "EncryptionPolicy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Security::EncryptionPolicy enumeración. Enumera las políticas de cifrado en C++."
type: docs
weight: 400
url: /es/cpp/system.net.security/encryptionpolicy/
---
## EncryptionPolicy enum


Enumera las políticas de cifrado.

```cpp
enum class EncryptionPolicy
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RequireEncryption | 0 | Requiere cifrado y nunca permite un cifrado 'Null'. |
| AllowNoEncryption | 1 | Prefiere usar cifrado completo pero se puede usar un cifrado 'Null' si el servidor está de acuerdo. |
| NoEncryption | 2 | Permite no cifrar y solicita que se use un cifrado 'Null' si el otro extremo puede manejar un cifrado 'Null'. |

## Ver también

* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
