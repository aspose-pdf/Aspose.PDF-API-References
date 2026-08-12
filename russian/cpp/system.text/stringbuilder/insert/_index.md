---
title: "System::Text::StringBuilder::Insert метод"
linktitle: "Вставить"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::StringBuilder::Insert метод. Вставляет символы в фиксированную позицию builder''s в C++."
type: docs
weight: 1300
url: /ru/cpp/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) method


Вставляет символы в фиксированную позицию построителя.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Позиция, в которую вставляются символы. |
| chars | const System::ArrayPtr\<char_t\>\& | [Array](../../../system/array/) для вставки среза из. |
| startIndex | int | [Array](../../../system/array/) начальный индекс среза. |
| charCount | int | [Array](../../../system/array/) длина среза. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, char_t) method


Вставляет символ в фиксированную позицию построителя.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Позиция, в которую вставляются символы. |
| ch | char_t | Символ для вставки. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, const String\&) method


Вставляет строку в фиксированную позицию построителя.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Позиция, в которую вставляются символы. |
| str | const String\& | [String](../../../system/string/) для вставки. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int, T) method


Вставляет значение в фиксированную позицию построителя.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


| Параметр | Описание |
| --- | --- |
| Параметр | тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Позиция, в которую вставляются символы. |
| value | T | Значение для форматирования и вставки. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Insert(int32_t, const String\&, int32_t) method


Вставляет повторяющуюся строку в фиксированную позицию построителя.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int32_t | Позиция, в которую вставляются символы. |
| value | const String\& | [String](../../../system/string/) для вставки. |
| count | int32_t | Сколько раз повторять строку **value**. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
