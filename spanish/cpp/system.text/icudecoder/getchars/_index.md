---
title: "System::Text::ICUDecoder::GetChars método"
linktitle: "GetChars"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::ICUDecoder::GetChars método. Obtenga los caracteres que resultan de decodificar un búfer en C++."
type: docs
weight: 500
url: /es/cpp/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Obtiene los caracteres que resultan de decodificar un búfer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | Bytes a decodificar. |
| byteIndex | int | Desplazamiento del búfer de entrada. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | ArrayPtr\<char_t\> | Buffer de caracteres de destino. |
| charIndex | int | Desplazamiento del arreglo de destino. |

### ReturnValue

Número de caracteres escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method


Obtiene los caracteres que resultan de decodificar un búfer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | Bytes a decodificar. |
| byteIndex | int | Desplazamiento del búfer de entrada. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | ArrayPtr\<char_t\> | Buffer de caracteres de destino. |
| charIndex | int | Desplazamiento del arreglo de destino. |
| flush | bool | Si es verdadero, limpia el estado interno del decodificador después del cálculo. |

### ReturnValue

Número de caracteres escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) method


Obtiene los caracteres que resultan de decodificar un búfer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const uint8_t * | Bytes a decodificar. |
| byteCount | int | Tamaño del búfer de entrada. |
| chars | char_t * | Buffer de caracteres de destino. |
| charCount | int | Tamaño del arreglo de destino. |
| flush | bool | Si es verdadero, limpia el estado interno del decodificador después del cálculo. |

### ReturnValue

Número de caracteres escritos.

## Ver también

* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
