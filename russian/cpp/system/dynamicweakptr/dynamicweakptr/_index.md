---
title: "Конструктор System::DynamicWeakPtr::DynamicWeakPtr"
linktitle: "DynamicWeakPtr"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::DynamicWeakPtr::DynamicWeakPtr. Копирующий конструктор умного указателя в C++."
type: docs
weight: 100
url: /ru/cpp/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) constructor


Создаёт копию умного указателя.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const DynamicWeakPtr_\& | Умный указатель, из которого копировать информацию о pointee. |

## См. также

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) constructor


Создаёт копию умного указателя.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```


| Параметр | Описание |
| --- | --- |
| Q | Тип объекта, на который указывает исходный указатель. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Умный указатель, из которого копировать информацию о pointee. |

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) constructor


Создаёт копию умного указателя.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Умный указатель, из которого копировать информацию о pointee. |

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) constructor


Создаёт умный указатель, указывающий на заданный объект.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| объект | Pointee_ * | Pointee. |

## См. также

* Typedef [Pointee_](../pointee_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) constructor


Создаёт умный указатель перемещением.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | SmartPtr_\&& | Умный указатель, из которого перемещается информация об объекте. Становится непригодным после вызова. |

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) constructor


Создаёт нулевой умный указатель.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## См. также

* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
