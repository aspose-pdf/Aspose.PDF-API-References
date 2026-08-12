---
title: "System::Text::Encoder::GetByteCount method"
linktitle: "GetByteCount"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::Encoder::GetByteCount method. Obtiene el número de bytes necesarios para codificar un búfer en C++."
type: docs
weight: 400
url: /es/cpp/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


Obtiene el número de bytes necesarios para codificar un búfer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Caracteres a codificar. |
| index | int | Desplazamiento de [Buffer](../../../system/buffer/). |
| count | int | Número de caracteres a codificar. |
| flush | bool | Si es verdadero, limpia el estado interno del codificador después del cálculo. |

### ReturnValue

Número de bytes requeridos para codificar el búfer.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoder::GetByteCount(const char_t *, int, bool) method


Obtiene el número de bytes necesarios para codificar un búfer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| count | int | Número de caracteres a codificar. |
| flush | bool | Si es verdadero, limpia el estado interno del codificador después del cálculo. |

### ReturnValue

Número de bytes requeridos para codificar el búfer.

## Ver también

* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
