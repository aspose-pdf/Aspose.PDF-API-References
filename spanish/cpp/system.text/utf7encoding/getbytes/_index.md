---
title: "System::Text::UTF7Encoding::GetBytes método"
linktitle: "GetBytes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::UTF7Encoding::GetBytes method. Obtenga los bytes que resultan de codificar un búfer de caracteres en C++."
type: docs
weight: 500
url: /es/cpp/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Caracteres a codificar. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Caracteres a codificar. |
| char_index | int | Inicio de la porción de carácter. |
| char_count | int | Número de caracteres a convertir. |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) para colocar caracteres. |
| byte_index | int | Desplazamiento del buffer de salida. |

### ReturnValue

Número de bytes escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Caracteres a codificar. |
| índice | int | Inicio de la porción de carácter. |
| count | int | Número de caracteres a convertir. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| char_count | int | Número de caracteres a convertir. |
| bytes | uint8_t * | [Buffer](../../../system/buffer/) para colocar caracteres. |
| byte_count | int | Tamaño del búfer de salida. |

### ReturnValue

Número de bytes escritos.

## Ver también

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const String\&) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) para codificar. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) para codificar. |
| char_index | int | Inicio de la porción de carácter. |
| char_count | int | Número de caracteres a convertir. |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) para colocar caracteres. |
| byte_index | int | Desplazamiento del buffer de salida. |

### ReturnValue

Número de bytes escritos.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Caracteres a codificar. |
| índice | int | Inicio de la porción de carácter. |
| count | int | Número de caracteres a convertir. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Caracteres a codificar. |
| índice | int | Inicio de la porción de carácter. |
| count | int | Número de caracteres a convertir. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Caracteres a codificar. |
| char_index | int | Inicio de la porción de carácter. |
| char_count | int | Número de caracteres a convertir. |
| bytes | System::Details::ArrayView\<uint8_t\> | [Buffer](../../../system/buffer/) para colocar caracteres. |
| byte_index | int | Desplazamiento del buffer de salida. |

### ReturnValue

Número de bytes escritos.

## Ver también

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method


Obtiene los bytes resultantes de codificar un búfer de caracteres.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Caracteres a codificar. |
| char_index | int | Inicio de la porción de carácter. |
| char_count | int | Número de caracteres a convertir. |
| bytes | System::Details::StackArray\<uint8_t, SB\>\& | [Buffer](../../../system/buffer/) para colocar caracteres. |
| byte_index | int | Desplazamiento del buffer de salida. |

### ReturnValue

Número de bytes escritos.

## Ver también

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
