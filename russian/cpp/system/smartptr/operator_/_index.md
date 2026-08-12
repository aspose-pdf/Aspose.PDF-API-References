---
title: "System::SmartPtr::operator* method"
linktitle: "operator*"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::SmartPtr::operator* method. Получает ссылку на указанный объект. Утверждает, что указатель не равен null в C++."
type: docs
weight: 2500
url: /ru/cpp/system/smartptr/operator_/
---
## SmartPtr::operator* method


Получает ссылку на объект, на который указывает указатель. Проверяется, что указатель не равен null.

```cpp
Pointee_ & System::SmartPtr<T>::operator*() const
```


### ReturnValue

Ссылка на указанный объект.

## См. также

* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
заголовок: System::SmartPtr::operator< method
linktitle: operator<
second_title: Aspose.PDF для C++ справочник API
описание: 'System::SmartPtr::operator< method. Обеспечивает семантику сравнения на меньше для класса SmartPtr в C++.'
type: docs
вес: 2700
url: /cpp/system/smartptr/operator_/
---
## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


Обеспечивает семантику сравнения на меньше для класса [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


| Параметр | Описание |
| --- | --- |
| Y | Тип указателя, с которым сравнивается текущий. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | SmartPtr\<Y\> const\& | Указатель, с которым сравнивается текущий. |

### ReturnValue

Истина, если объект, на который ссылается [SmartPtr](../), 'меньше' x, иначе ложь.

## См. также

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::operator<(Y *) const method


Обеспечивает семантику сравнения на меньше для класса [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


| Параметр | Описание |
| --- | --- |
| Y | Тип указателя, с которым сравнивается текущий. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| p | Y * | Указатель, с которым сравнивается текущий. |

### ReturnValue

Истина, если объект, на который ссылается [SmartPtr](../), 'меньше' p, иначе ложь.

## См. также

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
