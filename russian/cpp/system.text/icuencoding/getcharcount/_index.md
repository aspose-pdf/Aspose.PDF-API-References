---
title: "System::Text::ICUEncoding::GetCharCount метод"
linktitle: "GetCharCount"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::ICUEncoding::GetCharCount метод. Получить количество символов, необходимых для декодирования байтового буфера в C++."
type: docs
weight: 400
url: /ru/cpp/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) method


Получить количество символов, необходимое для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | ArrayPtr\<uint8_t\> | Байты для декодирования. |

### ReturnValue

Количество символов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Получить количество символов, необходимое для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | ArrayPtr\<uint8_t\> | Байты для декодирования. |
| индекс | int | Начало среза. |
| count | int | Размер среза. |

### ReturnValue

Количество символов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetCharCount(const uint8_t *, int) method


Получить количество символов, необходимое для декодирования буфера байтов.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const uint8_t * | Байты для декодирования. |
| count | int | Количество байтов. |

### ReturnValue

Количество символов.

## См. также

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
