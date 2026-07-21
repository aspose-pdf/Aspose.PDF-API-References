---
title: "System::Security::Cryptography::CipherMode enumeración"
linktitle: "CipherMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::CipherMode enumeración. Modo de cifrado por bloques en C++."
type: docs
weight: 5300
url: /es/cpp/system.security.cryptography/ciphermode/
---
## CipherMode enum


Modo de cifrado por bloques.

```cpp
enum class CipherMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| CBC | 1 | Encadenamiento de bloques de cifrado que combina el bloque actual con el bloque anterior para mejorar el cifrado. |
| ECB | 2 | Modo de libro de códigos electrónico sin influencias entre bloques; resulta en un cifrado más débil. |
| OFB | 3 | Modo de retroalimentación de salida que maneja bloques de entrada grandes en piezas pequeñas. |
| CFB | 4 | Modo de retroalimentación de cifrado que maneja bloques de entrada grandes en piezas pequeñas. Las reglas de mezcla difieren de las de OFB. |
| CTS | 5 | Modo de robo de texto cifrado, se comporta como CBC para todos menos los dos últimos bloques de texto. |

## Ver también

* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
