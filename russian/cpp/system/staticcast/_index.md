---
title: "System::StaticCast метод"
linktitle: "StaticCast"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::StaticCast метод. Выполняет статическое приведение типов для объектов, не являющихся указателями, в C++."
type: docs
weight: 43300
url: /ru/cpp/system/staticcast/
---
## System::StaticCast(const TFrom\&) method


Выполняет статическое приведение типов для объектов, не являющихся указателями.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип. |
| TFrom | Тип источника. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const TFrom\& | Объект-источник. |

### ReturnValue

Результат приведения, если приведение разрешено.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(const TFrom\&) method


Выполняет статическое приведение объектов [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип [Exception](../exception/). |
| TFrom | Исходный тип [Exception](../exception/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const TFrom\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(const TFrom *) method


Специализация для арифметических типов.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(SmartPtr\<TFrom\> const\&) method


Выполняет статическое приведение объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого объекта. |
| TFrom | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(SmartPtr\<TFrom\>) method


Выполняет статическое приведение объектов к объектам [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип [Exception](../exception/). |
| TFrom | Тип [Object](../object/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(std::nullptr_t) method


Выполняет статическое приведение нулевых объектов.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого объекта. |

### ReturnValue

nullptr.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(TFrom) method


Специализация для арифметических типов.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(TTo) method


Обработать приведение из [String](../string/) в [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## См. также

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(WeakPtr\<TFrom\> const\&) method


Выполняет статическое приведение объектов [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого объекта. |
| TFrom | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
