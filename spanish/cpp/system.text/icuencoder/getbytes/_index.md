---
title: "System::Text::ICUEncoder::GetBytes método"
linktitle: "GetBytes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::ICUEncoder::GetBytes método. Obtiene los bytes que resultan de codificar un búfer en C++."
type: docs
weight: 500
url: /es/cpp/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method


Obtiene los bytes que resultan de codificar un búfer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Caracteres a codificar. |
| charIndex | int | Desplazamiento del arreglo de origen. |
| charCount | int | Longitud del subarreglo de origen. |
| bytes | ArrayPtr\<uint8_t\> | Búfer de bytes de destino. |
| byteIndex | int | Desplazamiento del búfer de destino. |
| flush | bool | Si es verdadero, limpia el estado interno del codificador después del cálculo. |

### ReturnValue

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method


Obtiene los bytes que resultan de codificar un búfer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| charCount | int | Longitud del arreglo de origen. |
| bytes | uint8_t * | Búfer de bytes de destino. |
| byteCount | int | Tamaño del búfer de destino. |
| flush | bool | Si es verdadero, limpia el estado interno del codificador después del cálculo. |

### ReturnValue

Número de bytes escritos.

## Ver también

* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
