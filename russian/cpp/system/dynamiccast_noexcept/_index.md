---
title: "System::DynamicCast_noexcept method"
linktitle: "DynamicCast_noexcept"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::DynamicCast_noexcept method. Старые устаревшие приведения типов. Будут удалены в будущих версиях C++."
type: docs
weight: 18100
url: /ru/cpp/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) method


Устаревшие приведения типов. Будут удалены в будущих версиях.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
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
## Примечания


Выполняет динамическое приведение объектов [Exception](../exception/). ## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте AsCast.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) method


Выполняет динамическое приведение объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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
## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) method


Выполняет динамическое приведение объектов к объектам [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
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
