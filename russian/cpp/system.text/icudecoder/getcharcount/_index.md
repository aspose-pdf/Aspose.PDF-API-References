---
title: "System::Text::ICUDecoder::GetCharCount метод"
linktitle: "GetCharCount"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::ICUDecoder::GetCharCount метод. Получает количество символов, необходимых для декодирования буфера в C++."
type: docs
weight: 400
url: /ru/cpp/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Получает количество символов, необходимых для декодирования буфера.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | ArrayPtr\<uint8_t\> | Байты для декодирования. |
| index | int | [Buffer](../../../system/buffer/) смещение. |
| count | int | Количество байтов для декодирования. |

### ReturnValue

Количество символов, необходимых для декодирования буфера.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method


Получает количество символов, необходимых для декодирования буфера.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | ArrayPtr\<uint8_t\> | Байты для декодирования. |
| index | int | [Buffer](../../../system/buffer/) смещение. |
| count | int | Количество байтов для декодирования. |
| flush | bool | Если true, очищает внутреннее состояние декодера после вычисления. |

### ReturnValue

Количество символов, необходимых для декодирования буфера.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetCharCount(const uint8_t *, int, bool) method


Получает количество символов, необходимых для декодирования буфера.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const uint8_t * | Байты для декодирования. |
| count | int | Количество байтов для декодирования. |
| flush | bool | Если true, очищает внутреннее состояние декодера после вычисления. |

### ReturnValue

Количество символов, необходимых для декодирования буфера.

## См. также

* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
