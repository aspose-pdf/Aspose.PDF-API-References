---
title: "Метод System::SmartPtr::operator="
linktitle: "operator="
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::SmartPtr::operator=. Копирующе‑присваивает объект SmartPtr. Выполняет необходимые преобразования типов в C++."
type: docs
weight: 2800
url: /ru/cpp/system/smartptr/operator=/
---
## SmartPtr::operator=(const SmartPtr\<Q\>\&) method


Копирующе‑присваивает объект [SmartPtr](../). Выполняет необходимые преобразования типов.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


| Параметр | Описание |
| --- | --- |
| Q | Тип объекта, на который указывает x. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Указатель для копирующего присваивания. |

### ReturnValue

Ссылка на этот объект.

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(const SmartPtr_\&) method


Копирующе‑присваивает объект [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const SmartPtr_\& | Указатель для копирующего присваивания. |

### ReturnValue

Ссылка на этот объект.

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(Pointee_ *) method


Присваивает неуправляемый указатель объекту [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| p | Pointee_ * | Значение указателя для присваивания. |

### ReturnValue

Ссылка на этот объект.

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(SmartPtr_\&&) method


Перемещающе‑присваивает объект [SmartPtr](../). x становится непригодным к использованию.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | SmartPtr_\&& | Указатель для перемещающего присваивания. |

### ReturnValue

Ссылка на этот объект.

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator=(std::nullptr_t) method


Устанавливает значение указателя в nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### ReturnValue

Ссылка на этот объект.

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
