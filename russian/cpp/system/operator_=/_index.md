---
title: "Метод System::operator<="
linktitle: "operator<="
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::operator<=. Определяет, меньше ли указанное значение или равно значению, представленному указанным объектом Nullable, применяя operator<=() к этим значениям в C++."
type: docs
weight: 32700
url: /ru/cpp/system/operator_=/
---
## System::operator<=(const T1\&, const Nullable\<T2\>\&) method


Определяет, меньше ли указанное значение или равно значению, представленному указанным объектом [Nullable](../nullable/), применяя [operator<=()](./) к этим значениям.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип первого сравниваемого значения |
| T2 | Базовый тип объекта [Nullable](../nullable/), представляющего второе сравниваемое значение |

| Параметр | Тип | Описание |
| --- | --- | --- |
| некоторые | const T1\& | Константная ссылка на значение, которое будет использоваться в качестве первого сравниваемого |
| other | const Nullable\<T2\>\& | Константная ссылка на объект [Nullable](../nullable/), значение которого будет использоваться в качестве второго сравниваемого |

### ReturnValue

true, если первый сравниваемый меньше или равен второму сравниваемому, иначе - false

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## См. также

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) method


Всегда возвращает false.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<=(std::nullptr_t, DateTime) method




```cpp
bool System::operator<=(std::nullptr_t, DateTime)
```

## См. также

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator<=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator<=(std::nullptr_t, TimeSpan)
```

## См. также

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
---
title: Метод System::operator>=
linktitle: operator>=
second_title: Aspose.PDF для C++ справочник API
description: 'Метод System::operator>=. Определяет, больше ли указанное значение или равно значению, представленному указанным объектом Nullable, применяя operator>=() к этим значениям в C++.'
type: docs
weight: 35400
url: /cpp/system/operator_=/
---
## System::operator>=(const T1\&, const Nullable\<T2\>\&) method


Определяет, больше ли указанное значение или равно значению, представленному указанным объектом [Nullable](../nullable/), применяя [operator>=()](./) к этим значениям.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип первого сравниваемого значения |
| T2 | Базовый тип объекта [Nullable](../nullable/), представляющего второе сравниваемое значение |

| Параметр | Тип | Описание |
| --- | --- | --- |
| некоторые | const T1\& | Константная ссылка на значение, которое будет использоваться в качестве первого сравниваемого |
| other | const Nullable\<T2\>\& | Константная ссылка на объект [Nullable](../nullable/), значение которого будет использоваться в качестве второго сравниваемого |

### ReturnValue

true, если первый сравниваемый больше или равен второму сравниваемому, иначе - false

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## См. также

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) method


Всегда возвращает false.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>=(std::nullptr_t, DateTime) method




```cpp
bool System::operator>=(std::nullptr_t, DateTime)
```

## См. также

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator>=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator>=(std::nullptr_t, TimeSpan)
```

## См. также

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
