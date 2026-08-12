---
title: "Метод System::ObjectExt::Equals"
linktitle: "Equals"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ObjectExt::Equals. Замена вызовов C# Object.Equals, работающая для любого типа в C++. Перегрузка для строкового литерала со сравнением строк в C++."
type: docs
weight: 800
url: /ru/cpp/system/objectext/equals/
---
## ObjectExt::Equals(const char_t(&), String) method


Замена вызовов C# [Object.Equals](../../object/equals/) , работающая для любого типа в C++. Перегрузка для строкового литерала со сравнением строк.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


| Параметр | Описание |
| --- | --- |
| N | [String](../../string/) размер литерала. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) литерал. |
| another | String | [String](../../string/). |

### ReturnValue

True, если строки совпадают, иначе false.

## См. также

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const double\&, const double\&) method


Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const double\& | Значение плавающей запятой слева. |
| другой | const double\& | Значение плавающей запятой справа. |

### ReturnValue

Истина, если **obj** и **another** оба NaN или равны, иначе ложь.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const float\&, const float\&) method


Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const float\& | Значение плавающей запятой слева. |
| другой | const float\& | Значение плавающей запятой справа. |

### ReturnValue

Истина, если **obj** и **another** оба NaN или равны, иначе ложь.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Замена вызовов C# [Object.Equals](../../object/equals/) работающих с любым типом в C++. Перегрузка для типов умных указателей.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Параметр | Описание |
| --- | --- |
| T | Тип первого объекта. |
| T2 | Тип второго объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | Первый объект. |
| другой | const T2\& | Второй объект. |

### ReturnValue

Истина, если объекты считаются равными, иначе ложь.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Замена вызовов C# [Object.Equals](../../object/equals/) работающих с любым типом в C++. Перегрузка для скалярных типов.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Параметр | Описание |
| --- | --- |
| T | Тип первого объекта. |
| T2 | Тип второго объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | Первый объект. |
| другой | const T2\& | Второй объект. |

### ReturnValue

Истина, если объекты считаются равными, иначе ложь.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(T, const T2\&) method


Замена вызовов C# [Object.Equals](../../object/equals/) работающих с любым типом в C++. Перегрузка для структурных типов.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


| Параметр | Описание |
| --- | --- |
| T | Тип первого объекта. |
| T2 | Тип второго объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T | Первый объект. |
| другой | const T2\& | Второй объект. |

### ReturnValue

Истина, если объекты считаются равными, иначе ложь.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
