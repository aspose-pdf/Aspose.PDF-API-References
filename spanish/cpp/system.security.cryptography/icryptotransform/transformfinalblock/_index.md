---
title: "System::Security::Cryptography::ICryptoTransform::TransformFinalBlock method"
linktitle: "TransformFinalBlock"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::ICryptoTransform::TransformFinalBlock method. Procesa el último bloque de datos y calcula el valor de salida en C++."
type: docs
weight: 400
url: /es/cpp/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock method


Procesa el último bloque de datos y calcula el valor de salida.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) para leer datos de. |
| inputOffset | int | Desplazamiento del búfer de entrada. |
| inputCount | int | Número de bytes a procesar. |

### ReturnValue

Salida calculada para toda la secuencia de entrada.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
