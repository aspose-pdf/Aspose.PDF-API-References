---
title: "Método System::Security::Cryptography::ToBase64Transform::TransformBlock"
linktitle: "TransformBlock"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Security::Cryptography::ToBase64Transform::TransformBlock. Procesa un bloque de datos y copia los datos al arreglo de salida en C++."
type: docs
weight: 800
url: /es/cpp/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock method


Procesa un bloque de datos y copia los datos al arreglo de salida.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputBuffer | System::ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) para leer datos de. |
| inputOffset | int32_t | Desplazamiento del búfer de entrada. |
| inputCount | int32_t | Número de bytes a procesar. |
| outputBuffer | System::ArrayPtr\<uint8_t\> | Buffer de salida donde copiar los datos; nullptr para no copiar. |
| outputOffset | int32_t | Desplazamiento del buffer de salida. |

### ReturnValue

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
