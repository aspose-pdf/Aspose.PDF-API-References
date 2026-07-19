---
title: "System::operator== method"
linktitle: "operator=="
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод operator== класса в C++."
type: docs
weight: 33200
url: /ru/cpp/system/operator==/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) method




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## См. также

* Class [ArraySegment](../arraysegment/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(Chars\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


| Параметр | Описание |
| --- | --- |
| Chars | [String](../string/) тип литерала. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | Chars\& | [String](../string/) литерал для сравнения. |
| right | const String\& | [String](../string/) для сравнения. |

### ReturnValue

true, если строки совпадают, иначе false.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const SharedPtr\<Object\>\&, const String\&) method


[Object](../object/) and string comparison.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| left | const SharedPtr\<Object\>\& | [Object](../object/) для преобразования в строку и сравнения. |
| right | const String\& | [String](../string/) для сравнения. |

### ReturnValue

true, если строковое представление объекта равно строке, иначе false.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) method


Определяет, равны ли URI, представленные текущим и указанным объектами.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uri1 | const SharedPtr\<Uri\>\& | Первый объект [Uri](../uri/) для сравнения |
| uri2 | const SharedPtr\<Uri\>\& | Второй объект [Uri](../uri/) для сравнения |

### ReturnValue

True, если URI равны, иначе - false.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [Uri](../uri/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) method


Сравнивает два умных указателя на равенство.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
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

True, если указатели совпадают, иначе false.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const SmartPtr\<X\>\&, const Y *) method


Сравнение равенства умного указателя с простым (C) указателем.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
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

True, если указатели совпадают, иначе false.

## См. также

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const T1\&, const Nullable\<T2\>\&) method


Определяет, равна ли указанная величина значению, представленному указанным объектом [Nullable](../nullable/), путем применения [operator==()](./) к этим значениям.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
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

True, если сравниваемые значения равны, иначе - false.

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const X *, const SmartPtr\<Y\>\&) method


Сравнение равенства умного указателя с простым (C) указателем.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
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

True, если указатели совпадают, иначе false.

## См. также

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## См. также

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, const Nullable\<T\>\&) method


Определяет, представляет ли указанный объект [Nullable](../nullable/) значение, равное null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| other | std::nullptr_t | Константная ссылка на объект [Nullable](../nullable/) для тестирования |

### ReturnValue

True, если указанный объект представляет значение null, иначе false.

## См. также

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, const String\&) method


Проверяет, является ли строка null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) для проверки. |

### ReturnValue

true, если строка равна null, иначе false.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, DateTime) method




```cpp
bool System::operator==(std::nullptr_t, DateTime)
```

## См. также

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) method


Проверяет, является ли умный указатель null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает указатель. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | std::nullptr_t | Указатель для проверки. |

### ReturnValue

True, если указатель равен null, иначе false.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, T const\&) method


Проверяет, является ли объект типа значения (переведённая структура C#, и т.д.) null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) для проверки. |

### ReturnValue

True, если объект равен null, иначе false.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator==(std::nullptr_t, TimeSpan)
```

## См. также

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(T\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


| Параметр | Описание |
| --- | --- |
| T | [String](../string/) тип указателя. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | T\& | [String](../string/) указатель для сравнения. |
| right | const String\& | [String](../string/) для сравнения. |

### ReturnValue

true, если строки совпадают, иначе false.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(T const\&, std::nullptr_t) method


Проверяет, является ли объект типа значения (переведённая структура C#, и т.д.) null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | T const\& | [Object](../object/) для проверки. |

### ReturnValue

True, если объект равен null, иначе false.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
