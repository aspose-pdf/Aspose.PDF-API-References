---
title: "Метод System::DynamicWeakPtr::operator="
linktitle: "operator="
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::DynamicWeakPtr::operator=. Копирующее присваивание умного указателя в C++."
type: docs
weight: 200
url: /ru/cpp/system/dynamicweakptr/operator=/
---
## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) method


Копирующее присваивание умного указателя.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


| Параметр | Описание |
| --- | --- |
| Q | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Указатель, из которого копируется значение. |

### ReturnValue

Ссылка на себя.

## См. также

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [SmartPtr](../../smartptr/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::operator=(const SmartPtr_\&) method


Копирующее присваивание умного указателя.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const SmartPtr_\& | Указатель, из которого копируется значение. |

### ReturnValue

Ссылка на себя.

## См. также

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::operator=(SmartPtr_\&&) method


Перемещающее присваивание умного указателя.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | SmartPtr_\&& | Указатель, из которого перемещается значение. |

### ReturnValue

Ссылка на себя.

## См. также

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::operator=(std::nullptr_t) method


Устанавливает умный указатель в null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### ReturnValue

Ссылка на себя.

## См. также

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) method


Назначает умный указатель.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| p | typename SmartPtr_::Pointee_ * | Значение указателя. |

### ReturnValue

Ссылка на себя.

## См. также

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
