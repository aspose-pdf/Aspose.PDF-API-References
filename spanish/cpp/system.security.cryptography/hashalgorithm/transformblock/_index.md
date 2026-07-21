---
title: "System::Security::Cryptography::HashAlgorithm::TransformBlock method"
linktitle: "TransformBlock"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Security::Cryptography::HashAlgorithm::TransformBlock. Procesa un bloque de datos y copia los datos al arreglo de salida en C++."
type: docs
weight: 800
url: /es/cpp/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock method


Procesa un bloque de datos y copia los datos al arreglo de salida.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) para leer datos de. |
| inputOffset | int | Desplazamiento del búfer de entrada. |
| inputCount | int | Número de bytes a procesar. |
| outputBuffer | ArrayPtr\<uint8_t\> | Buffer de salida donde copiar los datos; nullptr para no copiar. |
| outputOffset | int | Desplazamiento del buffer de salida. |

### ReturnValue

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
