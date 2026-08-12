---
title: "System::Object::Equals method"
linktitle: "Equals"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Object::Equals method. Сравнивает объекты, используя семантику C# Object.Equals в C++."
type: docs
weight: 300
url: /ru/cpp/system/object/equals/
---
## Object::Equals(ptr) method


Сравнивает объекты, используя семантику C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | ptr | [Object](../) для сравнения текущего объекта. |

### ReturnValue

Истина, если объекты считаются равными, и ложь в противном случае.

## См. также

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(double const\&, double const\&) method


Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | double const\& | Значение плавающей запятой слева. |
| objB | double const\& | Значение плавающей запятой справа. |

### ReturnValue

Истина, если **objA** и **objB** оба NaN или равны, иначе ложь.

## См. также

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(float const\&, float const\&) method


Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | float const\& | Значение плавающей запятой слева. |
| objB | float const\& | Значение плавающей запятой справа. |

### ReturnValue

Истина, если **objA** и **objB** оба NaN или равны, иначе ложь.

## См. также

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


Сравнивает объекты ссылочного типа в стиле C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип первого объекта для сравнения. |
| T2 | Тип второго объекта для сравнения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | T1 const\& | Первый объект для сравнения. |
| objB | T2 const\& | Второй объект для сравнения. |

### ReturnValue

Истина, если объекты совпадают либо по ссылке, либо семантически (по сравнению, похожему на [Object.Equals](./)), иначе ложь.

## См. также

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


Сравнивает объекты значимого типа в стиле C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип первого объекта для сравнения. |
| T2 | Тип второго объекта для сравнения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | T1 const\& | Первый объект для сравнения. |
| objB | T2 const\& | Второй объект для сравнения. |

### ReturnValue

Истина, если объекты считаются равными доступным оператором равенства, иначе ложь.

## См. также

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
