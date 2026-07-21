---
title: "Método System::Text::ICUDecoder::Convert"
linktitle: "Convertir"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Text::ICUDecoder::Convert. Convierte bytes a caracteres en C++."
type: docs
weight: 300
url: /es/cpp/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Convierte bytes a caracteres.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | Bytes a decodificar. |
| byteIndex | int | Desplazamiento del búfer de entrada. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | ArrayPtr\<char_t\> | Buffer de caracteres de destino. |
| charIndex | int | Desplazamiento del arreglo de destino. |
| charCount | int | Tamaño del arreglo de destino. |
| flush | bool | Si es verdadero, limpia el estado interno del decodificador después del cálculo. |
| bytesUsed | int\& | Referencia a la variable para almacenar el recuento de bytes leídos. |
| charsUsed | int\& | Referencia a la variable para almacenar el recuento de caracteres escritos. |
| completed | bool\& | Referencia a variable que se establecerá en true si el búfer de entrada se agotó y en false en caso contrario. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Convierte bytes a caracteres.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const uint8_t * | Bytes a decodificar. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | char_t * | Buffer de caracteres de destino. |
| charCount | int | Tamaño del arreglo de destino. |
| flush | bool | Si es verdadero, limpia el estado interno del decodificador después del cálculo. |
| bytesUsed | int\& | Referencia a la variable para almacenar el recuento de bytes leídos. |
| charsUsed | int\& | Referencia a la variable para almacenar el recuento de caracteres escritos. |
| completed | bool\& | Referencia a variable que se establecerá en true si el búfer de entrada se agotó y en false en caso contrario. |

## Ver también

* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
