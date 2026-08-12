---
title: "Метод System::DynamicCast"
linktitle: "DynamicCast"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::DynamicCast. Выполняет динамическое приведение объектов Exception в C++."
type: docs
weight: 17400
url: /ru/cpp/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) method


Выполняет динамическое приведение объектов [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
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
## System::DynamicCast(SmartPtr\<TFrom\> const\&) method


Выполняет динамическое приведение объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
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
## System::DynamicCast(SmartPtr\<TFrom\>) method


Разворачивает упакованный enum с помощью приведения.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого enum. |
| TFrom | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Указатель на объект, из которого нужно разворачивать данные. |

### ReturnValue

Развернутое значение enum.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(SmartPtr\<TFrom\>) method


Выполняет динамическое приведение объектов к объектам [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
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
## System::DynamicCast(std::nullptr_t) method


Выполняет динамическое приведение нулевых объектов.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
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
## System::DynamicCast(TFrom\&) method


Выполняет динамическое приведение объектов, не являющихся указателями.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип. |
| TFrom | Тип источника. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | TFrom\& | Объект-источник. |

### ReturnValue

Результат приведения.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(TFrom) method


Выполняет динамическое приведение из IntPtr в указатель.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип. |
| TFrom | Тип источника. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | TFrom | Исходное значение IntPtr. |

### ReturnValue

Результат приведения.

## Deprecated
Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
