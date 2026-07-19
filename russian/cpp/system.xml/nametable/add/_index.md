---
title: "System::Xml::NameTable::Add метод"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::NameTable::Add метод. Атомизирует указанную строку и добавляет её в NameTable в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml/nametable/add/
---
## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Атомизирует указанную строку и добавляет её в [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | const ArrayPtr\<char16_t\>\& | Массив символов, содержащий строку для добавления. |
| начало | int32_t | Нулевой индекс в массиве, указывающий первый символ строки. |
| len | int32_t | Количество символов в строке. |

### ReturnValue

Атомизированная строка или существующая строка, если она уже присутствует в [NameTable](../). Если **len** равно нулю, возвращается [String::Empty](../../../system/string/empty/).

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## NameTable::Add(const String\&) method


Атомизирует указанную строку и добавляет её в [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | const String\& | Строка для добавления. |

### ReturnValue

Атомизированная строка или существующая строка, если она уже присутствует в [NameTable](../).

## См. также

* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
