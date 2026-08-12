---
title: "System::operator!= метод"
linktitle: "operator!="
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод operator!= класса в C++."
type: docs
weight: 26600
url: /ru/cpp/system/operator!=/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) method




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## См. также

* Class [ArraySegment](../arraysegment/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(Chars\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


| Параметр | Описание |
| --- | --- |
| Chars | [String](../string/) тип литерала. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | Chars\& | [String](../string/) литерал для сравнения. |
| right | const String\& | [String](../string/) для сравнения. |

### ReturnValue

false, если строки совпадают, иначе true.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SharedPtr\<Object\>\&, const String\&) method


[Object](../object/) and string comparison.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| left | const SharedPtr\<Object\>\& | [Object](../object/) для преобразования в строку и сравнения. |
| right | const String\& | [String](../string/) для сравнения. |

### ReturnValue

false, если строковое представление объекта равно строке, иначе true.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) method


Определяет, не равны ли URI, представленные текущим и указанным объектами.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uri1 | const SharedPtr\<Uri\>\& | Первый объект [Uri](../uri/) для сравнения |
| uri2 | const SharedPtr\<Uri\>\& | Второй объект [Uri](../uri/) для сравнения |

### ReturnValue

True, если URI не равны, иначе - false

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [Uri](../uri/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) method


Сравнивает два умных указателя на неравенство.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает первый указатель. |
| Y | Тип объекта, на который указывает второй указатель. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | Первый указатель для сравнения. |
| y | const SmartPtr\<Y\>\& | Второй указатель для сравнения. |

### ReturnValue

Ложно, если указатели совпадают, иначе истинно.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const SmartPtr\<X\>\&, const Y *) method


Сравнение неравенства умного указателя с простым (C) указателем.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


| Параметр | Описание |
| --- | --- |
| X | Тип умного указателя. |
| Y | Тип простого указателя. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | Умный указатель для сравнения (левый). |
| y | const Y * | Указатель для сравнения (правый). |

### ReturnValue

Ложно, если указатели совпадают, иначе истинно.

## См. также

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const T1\&, const Nullable\<T2\>\&) method


Определяет, не равна ли указанная величина значению, представленному указанным объектом [Nullable](../nullable/), путем применения [operator!=()](./) к этим значениям.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
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

Истина, если сравниваемые значения не равны, иначе — ложь

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(const X *, const SmartPtr\<Y\>\&) method


Сравнение равенства умного указателя с простым (C) указателем.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


| Параметр | Описание |
| --- | --- |
| X | Тип простого указателя. |
| Y | Тип умного указателя. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const X * | Указатель для сравнения (правый). |
| y | const SmartPtr\<Y\>\& | Умный указатель для сравнения (левый). |

### ReturnValue

Ложно, если указатели совпадают, иначе истинно.

## См. также

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) method


Проверяет, что умный указатель не равен null.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает указатель. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | SmartPtr\\<X\\> const\\& | Указатель для проверки. |

### ReturnValue

Ложно, если указатель равен null, иначе истинно.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## См. также

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) method


Определяет, представляет ли указанный объект [Nullable](../nullable/) значение, не равное null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| other | std::nullptr_t | Константная ссылка на объект [Nullable](../nullable/) для тестирования |

### ReturnValue

true, если указанный объект представляет ненулевое значение, иначе false

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, const String\&) method


Проверяет, является ли строка null.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) для проверки. |

### ReturnValue

false, если строка null, иначе true.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, DateTime) method




```cpp
bool System::operator!=(std::nullptr_t, DateTime)
```

## См. также

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) method


Проверяет, что умный указатель не равен null.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает указатель. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | std::nullptr_t | Указатель для проверки. |

### ReturnValue

Ложно, если указатель равен null, иначе истинно.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator!=(std::nullptr_t, TimeSpan)
```

## См. также

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator!=(T\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


| Параметр | Описание |
| --- | --- |
| T | [String](../string/) тип указателя. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | T\& | [String](../string/) указатель для сравнения. |
| right | const String\& | [String](../string/) для сравнения. |

### ReturnValue

false, если строки совпадают, иначе true.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
