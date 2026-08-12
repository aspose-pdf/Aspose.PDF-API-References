---
title: "System::Security::Cryptography::HashAlgorithm::TransformFinalBlock method"
linktitle: "TransformFinalBlock"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::HashAlgorithm::TransformFinalBlock method. Procesa el último bloque de datos y calcula el hash en C++."
type: docs
weight: 900
url: /es/cpp/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock method


Procesa el último bloque de datos y calcula el hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) para leer datos de. |
| inputOffset | int | Desplazamiento del búfer de entrada. |
| inputCount | int | Número de bytes a procesar. |

### ReturnValue

Hash calculado para toda la secuencia de datos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
