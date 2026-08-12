---
title: "System::Globalization::CompareInfo::Compare метод"
linktitle: "Compare"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::CompareInfo::Compare метод. Сравнивает строки. В C++ поддерживаются только режимы Ordinal и OrdinalIgnoreCase."
type: docs
weight: 200
url: /ru/cpp/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const method


Сравнивает строки. Поддерживаются только режимы Ordinal и OrdinalIgnoreCase.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const String\& | Строка LHS. |
| b | const String\& | Строка RHS. |
| options | CompareOptions | [String](../../../system/string/) тип сравнения. |

### ReturnValue

Отрицательное значение, если строка LHS предшествует строке RHS, ноль, если они совпадают, положительное значение в остальных случаях.

## См. также

* Class [String](../../../system/string/)
* Enum [CompareOptions](../../compareoptions/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
## CompareInfo::Compare(const String\&, const String\&) const method


Сравнивает строки. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const String\& | Строка LHS. |
| string2 | const String\& | Строка RHS. |

### ReturnValue

Отрицательное значение, если строка LHS предшествует строке RHS, ноль, если они совпадают, положительное значение в остальных случаях.

## См. также

* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
## CompareInfo::Compare(const String\&, int, const String\&, int) const method


Сравнивает конечный раздел одной строки с конечным разделом второй строки. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const String\& | Первая строка. |
| offset1 | int | Начальный индекс символов в **string1**. |
| string2 | const String\& | Вторая строка. |
| offset2 | int | Начальный индекс символов в **string2**. |

### ReturnValue

Отрицательное значение, если первая часть строки предшествует второй части строки, ноль, если они совпадают, положительное значение в остальных случаях.

## См. также

* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const method


Сравнивает конечный раздел одной строки с конечным разделом второй строки с использованием методов сравнения строк. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const String\& | Первая строка. |
| offset1 | int | Начальный индекс символов в **string1**. |
| string2 | const String\& | Вторая строка. |
| offset2 | int | Начальный индекс символов в **string2**. |
| options | CompareOptions | [String](../../../system/string/) параметры сравнения. |

### ReturnValue

Отрицательное значение, если первая часть строки предшествует второй части строки, ноль, если они совпадают, положительное значение в остальных случаях.

## См. также

* Class [String](../../../system/string/)
* Enum [CompareOptions](../../compareoptions/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const method


Сравнивает часть одной строки с частью второй строки. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const String\& | Первая строка. |
| offset1 | int | Начальный индекс символов в **string1**. |
| length1 | int | Количество символов в **string1**, которые нужно сравнить. |
| string2 | const String\& | Вторая строка. |
| offset2 | int | Начальный индекс символов в **string2**. |
| length2 | int | Количество символов в **string2**, которые нужно сравнить. |

### ReturnValue

Отрицательное значение, если первая часть строки предшествует второй части строки, ноль, если они совпадают, положительное значение в остальных случаях.

## См. также

* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const method


Сравнивает часть одной строки с частью второй строки с использованием методов сравнения строк. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const String\& | Первая строка. |
| offset1 | int | Начальный индекс символов в **string1**. |
| length1 | int | Количество символов в **string1**, которые нужно сравнить. |
| string2 | const String\& | Вторая строка. |
| offset2 | int | Начальный индекс символов в **string2**. |
| length2 | int | Количество символов в **string2**, которые нужно сравнить. |
| options | CompareOptions | [String](../../../system/string/) параметры сравнения. |

### ReturnValue

Отрицательное значение, если первая часть строки предшествует второй части строки, ноль, если они совпадают, положительное значение в остальных случаях.

## См. также

* Class [String](../../../system/string/)
* Enum [CompareOptions](../../compareoptions/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
