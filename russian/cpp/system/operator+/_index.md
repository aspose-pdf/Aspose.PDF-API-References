---
title: "Метод System::operator+"
linktitle: "operator+"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::operator+. Конкатенация строк в C++."
type: docs
weight: 28300
url: /ru/cpp/system/operator+/
---
## System::operator+(const char_t, const String\&) method


[String](../string/) concatenation.

```cpp
String System::operator+(const char_t left, const String &right)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| лево | const char_t | Символ для конкатенации со строкой. |
| right | const String\& | [String](../string/) для конкатенации. |

### ReturnValue

Конкатенированная строка.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(const T\&, const Decimal\&) method


Возвращает новый экземпляр класса [Decimal](../decimal/), представляющий значение, являющееся суммой указанного значения и значения, представленного указанным объектом [Decimal](../decimal/).

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const T\& | Первый слагаемый |
| d | const Decimal\& | Константная ссылка на объект [Decimal](../decimal/), представляющий второй слагаемый |

### ReturnValue

Новый экземпляр класса [Decimal](../decimal/), представляющий значение, являющееся суммой **x** и значения, представленного **d**.

## См. также

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(const T1\&, const Nullable\<T2\>\&) method


Суммирует значения, не допускающие null, и значения, допускающие null.

```cpp
template<typename T1,typename T2,typename> System::Nullable<decltype(some+other.get_Value())> System::operator+(const T1 &some, const Nullable<T2> &other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип левого операнда. |
| T2 | Тип правого операнда. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| некоторые | const T1\& | Левый операнд. |
| другое | const Nullable\<T2\>\& | Правый операнд. |

### ReturnValue

Результат суммирования.

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) method


Подключает все обратные вызовы из делегата правой стороны к концу списка обратных вызовов делегата левой стороны.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Делегат, к которому добавляются обратные вызовы. |
| rhv | MulticastDelegate\<T\> | Делегат, чьи обратные вызовы добавляются. |

### ReturnValue

Возвращает делегат, содержащий обратные вызовы значения левой стороны, а затем обратные вызовы правой стороны.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(T\&, const String\&) method


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


| Параметр | Описание |
| --- | --- |
| T | [String](../string/) тип литерала. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| лево | T\& | Литерал для конкатенации со строкой. |
| right | const String\& | [String](../string/) для конкатенации. |

### ReturnValue

Конкатенированная строка.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(T\&, const String\&) method


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


| Параметр | Описание |
| --- | --- |
| T | [String](../string/) тип указателя. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | T\& | [String](../string/) указатель для конкатенации со строкой. |
| right | const String\& | [String](../string/) для конкатенации. |

### ReturnValue

Конкатенированная строка.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
