---
title: "Метод System::String::CopyTo"
linktitle: "CopyTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::String::CopyTo. Копирует символы строки в существующие элементы массива. В C++ изменение размера не выполняется."
type: docs
weight: 700
url: /ru/cpp/system/string/copyto/
---
## String::CopyTo method


Копирует символы строки в существующие элементы массива. Изменение размера не производится.

```cpp
void System::String::CopyTo(int sourceIndex, const ArrayPtr<char_t> &destination, int destinationIndex, int count) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceIndex | int | Индекс в строке, с которого начинать чтение. |
| destination | const ArrayPtr\<char_t\>\& | Массив назначения. |
| destinationIndex | int | Индекс в массиве, с которого начинать запись. |
| count | int | Количество символов для копирования. |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
