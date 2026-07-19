---
title: "System::StaticCastArray method"
linktitle: "StaticCastArray"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::StaticCastArray method. Выполняет приведение элементов указанного массива к другому типу. Переопределение для случаев, когда From является объектом SmartPtr в C++."
type: docs
weight: 44600
url: /ru/cpp/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Выполняет приведение элементов указанного массива к другому типу. Переопределение для случаев, когда From является объектом [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Параметр | Описание |
| --- | --- |
| К | Тип, к которому следует привести элементы указанного массива |
| От | Тип элементов массива, элементы которого необходимо привести |

| Параметр | Тип | Описание |
| --- | --- | --- |
| от | const System::SharedPtr\<System::Array\<From\>\>\& | Умный указатель на массив, содержащий элементы для приведения |

### ReturnValue

Указатель на новый массив, содержащий элементы типа **To**, эквивалентные элементам **from**

## Deprecated
Добавлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Выполняет приведение элементов указанного массива к другому типу. Переопределение для случаев, когда From является Boxable, а To — [Object](../object/)[]

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Параметр | Описание |
| --- | --- |
| К | Тип, к которому следует привести элементы указанного массива |
| От | Тип элементов массива, элементы которого необходимо привести |

| Параметр | Тип | Описание |
| --- | --- | --- |
| от | const System::SharedPtr\<System::Array\<From\>\>\& | Умный указатель на массив, содержащий элементы для приведения |

### ReturnValue

Указатель на новый массив, содержащий элементы типа **To**, эквивалентные элементам **from**

## Deprecated
Добавлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
