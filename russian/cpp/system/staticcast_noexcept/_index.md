---
title: "метод System::StaticCast_noexcept"
linktitle: "StaticCast_noexcept"
second_title: "Справочник API Aspose.PDF для C++"
description: "метод System::StaticCast_noexcept. Выполняет статическое приведение объектов [Exception](../exception/) в C++."
type: docs
weight: 44200
url: /ru/cpp/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(const TFrom\&) method


Выполняет статическое приведение объектов [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип [Exception](../exception/). |
| TFrom | Исходный тип [Exception](../exception/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const TFrom\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено, иначе nullptr.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте AsCast.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) method


Выполняет статическое приведение объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого объекта. |
| TFrom | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено, иначе nullptr.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте AsCast.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(SmartPtr\<TFrom\>) method


Выполняет статическое приведение объектов к объектам [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип [Exception](../exception/). |
| TFrom | Тип [Object](../object/). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено, иначе nullptr.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте AsCast.

## См. также

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) method


Выполняет статическое приведение объектов [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого объекта. |
| TFrom | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Указатель источника. |

### ReturnValue

Результат приведения, если приведение разрешено, иначе nullptr.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте AsCast.

## См. также

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
