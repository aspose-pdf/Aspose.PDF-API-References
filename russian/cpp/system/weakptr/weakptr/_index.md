---
title: "Конструктор System::WeakPtr::WeakPtr"
linktitle: "WeakPtr"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::WeakPtr::WeakPtr. Создаёт слабый указатель, ссылающийся на тот же указатель, на который указывает x, в C++."
type: docs
weight: 100
url: /ru/cpp/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructor


Создаёт слабый указатель, ссылающийся на тот же указатель, на который указывает x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


| Параметр | Описание |
| --- | --- |
| Q | Тип pointee исходного указателя. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Указатель, из которого копировать значение pointee. |

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const SmartPtr_\&) constructor


Создаёт слабый указатель, ссылающийся на тот же указатель, на который указывает ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Указатель, из которого копировать значение pointee. |

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructor


Создаёт слабый указатель копирующим конструктором.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


| Параметр | Описание |
| --- | --- |
| Q | Тип исходного объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const WeakPtr\<Q\>\& | Указатель, из которого копировать значение pointee. |

## См. также

* Class [WeakPtr](../)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr_\&) constructor


Создаёт слабый указатель копирующим конструктором.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const WeakPtr_\& | Указатель, из которого копировать значение pointee. |

## См. также

* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(Pointee_ *) constructor


Создаёт слабый указатель на заданный объект.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| object | Pointee_ * | [Object](../../object/) для создания слабого указателя. |

## См. также

* Typedef [Pointee_](../pointee_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(SmartPtr_\&&) constructor


Создаёт слабый указатель перемещающим конструктором.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | SmartPtr_\&& | Указатель, из которого перемещать значение pointee. |

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## WeakPtr::WeakPtr(std::nullptr_t) constructor


Создаёт нулевой указатель.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## См. также

* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
