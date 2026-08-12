---
title: "System::Text::Encoding::Convert метод"
linktitle: "Преобразовать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::Encoding::Convert метод. Преобразует байты между двумя кодировками в C++."
type: docs
weight: 3000
url: /ru/cpp/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) method


Преобразует байты между двумя кодировками.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| src_encoding | const EncodingPtr\& | Исходная кодировка. |
| dst_encoding | const EncodingPtr\& | Целевая кодировка. |
| байты | const ArrayPtr\<uint8_t\>\& | Байты для преобразования. |

### ReturnValue

Преобразованные байты.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) method


Преобразует байты между двумя кодировками.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| src_encoding | const EncodingPtr\& | Исходная кодировка. |
| dst_encoding | const EncodingPtr\& | Целевая кодировка. |
| байты | const ArrayPtr\<uint8_t\>\& | Байты для преобразования. |
| индекс | int | Начало среза. |
| count | int | Размер среза. |

### ReturnValue

Преобразованные байты.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
