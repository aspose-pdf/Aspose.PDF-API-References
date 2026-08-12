---
title: "Метод System::String::LastIndexOf"
linktitle: "LastIndexOf"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::String::LastIndexOf. Обратный поиск символа в C++."
type: docs
weight: 2300
url: /ru/cpp/system/string/lastindexof/
---
## String::LastIndexOf(char_t) const method


Обратный поиск символа.

```cpp
int System::String::LastIndexOf(char_t value) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Искомый символ. |

### ReturnValue

[Index](../../index/) of last character position or -1 if not found.

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(char_t, int32_t) const method


Обратный поиск символа.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Искомый символ. |
| startIndex | int32_t | [Index](../../index/) для начала поиска с. |

### ReturnValue

[Index](../../index/) of last character position since startIndex or -1 if not found.

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(char_t, int32_t, int32_t) const method


Обратный поиск символа.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Искомый символ. |
| startIndex | int32_t | [Index](../../index/) для начала поиска с. |
| count | int32_t | Количество символов для просмотра |

### ReturnValue

[Index](../../index/) of last character position since startIndex or -1 if not found.

## См. также

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int, System::StringComparison) const method


Обратный поиск подстроки.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) режим. |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## См. также

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int) const method


Обратный поиск подстроки.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, System::StringComparison) const method


Обратный поиск подстроки.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Подстрока для поиска. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) режим. |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns string length.

## См. также

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::LastIndexOf(const String\&, int, int, StringComparison) const method


Обратный поиск подстроки.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |
| count | int | Количество символов для просмотра. |
| comparisonType | StringComparison | [Comparison](../../comparison/) режим. |

### ReturnValue

[Index](../../index/) of last found substring or -1 if not found. For empty lookup string, always returns startIndex+count.

## См. также

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
