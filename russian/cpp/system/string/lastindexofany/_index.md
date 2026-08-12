---
title: "Метод System::String::LastIndexOfAny"
linktitle: "LastIndexOfAny"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::String::LastIndexOfAny. Ищет любой из переданных символов по всей строке в обратном порядке. Сравнивает последний символ строки со всеми символами в anyOf, затем сравнивает предыдущий и так далее. Возвращает индекс первого найденного совпадения в C++."
type: docs
weight: 2400
url: /ru/cpp/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method


Ищет любой из переданных символов по всей строке в обратном порядке. Сравнивает последний символ строки со всеми символами в anyOf, затем сравнивает предыдущий и так далее. Возвращает индекс первого найденного совпадения.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) символов для поиска. Порядок не имеет значения. |

### ReturnValue

[Index](../../index/) of the last matching character or -1 if not found.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Ищет любой из переданных символов в подстроке в обратном порядке. Сравнивает последний символ строки со всеми символами в anyOf, затем сравнивает предыдущий и так далее. Возвращает индекс первого найденного совпадения.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) символов для поиска. Порядок не имеет значения. |
| startindex | int32_t | [Index](../../index/) для начала поиска. |

### ReturnValue

[Index](../../index/) of the last matching character or -1 if not found.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Ищет любой из переданных символов в подстроке в обратном порядке. Сравнивает последний символ строки со всеми символами в anyOf, затем сравнивает предыдущий и так далее. Возвращает индекс первого найденного совпадения.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) символов для поиска. Порядок не имеет значения. |
| startindex | int32_t | [Index](../../index/) для начала поиска. |
| count | int32_t | Количество символов для просмотра. |

### ReturnValue

[Index](../../index/) of the last matching character or -1 if not found.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
