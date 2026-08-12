---
title: "Метод System::String::IndexOfAny"
linktitle: "IndexOfAny"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::String::IndexOfAny. Поиск символа вперёд в C++."
type: docs
weight: 1500
url: /ru/cpp/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method


Прямой поиск символа.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Искомый символ. |
| startIndex | int | [Index](../../index/) для начала поиска с. |

### ReturnValue

[Index](../../index/) of first character position since startIndex or -1 if not found.

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method


Ищет любой из переданных символов во всей строке. Сравнивает первый символ строки со всеми символами в anyOf, затем сравнивает второй и так далее. Возвращает индекс первого символа, совпавшего с любым из целевых символов.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) символов для поиска. Порядок не имеет значения. |

### ReturnValue

[Index](../../index/) of the first matching character or -1 if not found.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Ищет любой из переданных символов в подстроке. Сравнивает первый символ строки со всеми символами в anyOf, затем сравнивает второй и так далее. Возвращает индекс первого символа, совпавшего с любым из целевых символов.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) символов для поиска. Порядок не имеет значения. |
| startindex | int32_t | [Index](../../index/) для начала поиска. |

### ReturnValue

[Index](../../index/) of the first matching character or -1 if not found.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Ищет любой из переданных символов в подстроке. Сравнивает первый символ строки со всеми символами в anyOf, затем сравнивает второй и так далее. Возвращает индекс первого символа, совпавшего с любым из целевых символов.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) символов для поиска. Порядок не имеет значения. |
| startindex | int32_t | [Index](../../index/) для начала поиска. |
| count | int32_t | Количество символов для просмотра. |

### ReturnValue

[Index](../../index/) of the first matching character or -1 if not found.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::IndexOfAny(const String\&, int) const method


Соответственно ищет все символы строки str в данном объекте. Если найден первый символ, возвращается его позиция, иначе ищется второй и так далее.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | [String](../) символов для поиска. Порядок символов имеет значение. |
| startIndex | int | Позиция, с которой начинать поиск. |

### ReturnValue

[Index](../../index/) of first found character or -1 if none is found.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
