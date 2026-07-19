---
title: "System::Text::StringBuilder::Append метод"
linktitle: "Добавить"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::StringBuilder::Append метод. Добавляет символ в builder в C++."
type: docs
weight: 300
url: /ru/cpp/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) method


Добавляет символ в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Значение символа. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(char_t, int) method


Добавляет символы в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Значение символа. |
| count | int | Сколько раз повторять вставляемый символ. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const ArrayPtr\<char_t\>\&) method


Добавляет массив символов в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const ArrayPtr\<char_t\>\& | Символы для добавления. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) method


Добавляет срез массива символов в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const ArrayPtr\<char_t\>\& | Символы для добавления. |
| startIndex | int | Индекс начала среза. |
| charCount | int | Длина среза. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) method


Добавляет содержимое построителя в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| builder | const SharedPtr\<StringBuilder\>\& | Конструктор для добавления содержимого из. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const SharedPtr\<T\>\&) method


Добавляет строковое представление объекта в построитель.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


| Параметр | Описание |
| --- | --- |
| T | [Object](../../../system/object/) тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const SharedPtr\<T\>\& | [Object](../../../system/object/) для сериализации и добавления. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const String\&) method


Добавляет строку в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | [String](../../../system/string/) для добавления. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(const String\&, int, int) method


Добавляет срез строки в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | [String](../../../system/string/) для добавления. |
| startIndex | int | Индекс начала среза. |
| charCount | int | Длина среза. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(double) method


Добавляет значение с плавающей точкой в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| df | double | Значение для сериализации и добавления. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(E) method


Добавляет строковое представление значения перечисления в построитель.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


| Параметр | Описание |
| --- | --- |
| E | [Enum](../../../system/enum/) тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| e | E | Значение для сериализации и добавления. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(float) method


Добавляет значение с плавающей точкой в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| f | float | Значение для сериализации и добавления. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(int) method


Добавляет целочисленное значение в построитель.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int | Значение для сериализации и добавления. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::Append(T) method


Добавляет арифметическое значение в построитель.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


| Параметр | Описание |
| --- | --- |
| T | Арифметический тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T | Значение для сериализации и добавления. |

### ReturnValue

Этот указатель.

## См. также

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
