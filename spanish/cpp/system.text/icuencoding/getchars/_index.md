---
title: "Método System::Text::ICUEncoding::GetChars"
linktitle: "GetChars"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Text::ICUEncoding::GetChars. Obtiene los caracteres que resultan de decodificar un búfer de bytes en C++."
type: docs
weight: 500
url: /es/cpp/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) method


Obtiene los caracteres resultantes de decodificar un búfer de bytes.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) para leer bytes de. |

### ReturnValue

[Buffer](../../../system/buffer/) of decoded characters.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Obtiene los caracteres resultantes de decodificar un búfer de bytes.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) para leer bytes de. |
| byte_index | int | Desplazamiento del búfer de entrada. |
| byte_count | int | Tamaño del búfer de entrada. |
| chars | ArrayPtr\<char_t\> | [Buffer](../../../system/buffer/) para colocar caracteres. |
| char_index | int | Desplazamiento del buffer de salida. |

### ReturnValue

Número de caracteres escritos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method


Obtiene los caracteres resultantes de decodificar un búfer de bytes.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) para leer bytes de. |
| índice | int | Desplazamiento del búfer de entrada. |
| count | int | Tamaño del búfer de entrada. |

### ReturnValue

[Buffer](../../../system/buffer/) of decoded characters.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) method


Obtiene los caracteres resultantes de decodificar un búfer de bytes.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const uint8_t * | [Buffer](../../../system/buffer/) para leer bytes de. |
| byte_count | int | Tamaño del búfer de entrada. |
| chars | char_t * | [Buffer](../../../system/buffer/) para colocar caracteres. |
| char_count | int | Tamaño del búfer de salida. |

### ReturnValue

Número de caracteres escritos.

## Ver también

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
