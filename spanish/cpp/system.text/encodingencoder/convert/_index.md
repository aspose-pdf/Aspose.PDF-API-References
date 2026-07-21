---
title: "System::Text::EncodingEncoder::Convert método"
linktitle: "Convertir"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::EncodingEncoder::Convert método. Convierte caracteres a bytes en C++."
type: docs
weight: 100
url: /es/cpp/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method


Convierte caracteres a bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Caracteres a codificar. |
| charIndex | int | Desplazamiento del búfer de entrada. |
| charCount | int | Tamaño del búfer de entrada. |
| bytes | ArrayPtr\<uint8_t\> | Búfer de bytes de destino. |
| byteIndex | int | Desplazamiento del arreglo de destino. |
| byteCount | int | Tamaño del arreglo de destino. |
| flush | bool | Si es verdadero, limpia el estado interno del codificador después del cálculo. |
| charsUsed | int\& | Referencia a variable para almacenar el recuento de caracteres leídos. |
| bytesUsed | int\& | Referencia a variable para almacenar el recuento de bytes escritos. |
| completed | bool\& | Referencia a variable que se establecerá en true si el búfer de entrada se agotó y en false en caso contrario. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method


Convierte caracteres a bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| charCount | int | Tamaño del búfer de entrada. |
| bytes | uint8_t * | Búfer de bytes de destino. |
| byteCount | int | Tamaño del arreglo de destino. |
| flush | bool | Si es verdadero, limpia el estado interno del codificador después del cálculo. |
| charsUsed | int\& | Referencia a variable para almacenar el recuento de caracteres leídos. |
| bytesUsed | int\& | Referencia a variable para almacenar el recuento de bytes escritos. |
| completed | bool\& | Referencia a variable que se establecerá en true si el búfer de entrada se agotó y en false en caso contrario. |

## Ver también

* Class [EncodingEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
