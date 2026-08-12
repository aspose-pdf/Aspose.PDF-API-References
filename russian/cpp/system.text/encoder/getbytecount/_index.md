---
title: "System::Text::Encoder::GetByteCount метод"
linktitle: "GetByteCount"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::Encoder::GetByteCount метод. Получает количество байтов, необходимых для кодирования буфера в C++."
type: docs
weight: 400
url: /ru/cpp/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


Получает количество байтов, необходимых для кодирования буфера.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | ArrayPtr\<char_t\> | Символы для кодирования. |
| index | int | [Buffer](../../../system/buffer/) смещение. |
| count | int | Количество символов для кодирования. |
| flush | bool | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### ReturnValue

Количество байтов, необходимых для кодирования буфера.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoder::GetByteCount(const char_t *, int, bool) method


Получает количество байтов, необходимых для кодирования буфера.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| символы | const char_t * | Символы для кодирования. |
| count | int | Количество символов для кодирования. |
| flush | bool | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### ReturnValue

Количество байтов, необходимых для кодирования буфера.

## См. также

* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
