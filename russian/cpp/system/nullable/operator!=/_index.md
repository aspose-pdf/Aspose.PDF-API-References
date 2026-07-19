---
title: "System::Nullable::operator!= метод"
linktitle: "operator!="
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Nullable::operator!= метод. Определяет, не равна ли величина, представленная текущим объектом, величине, представленной указанным объектом Nullable в C++."
type: docs
weight: 1000
url: /ru/cpp/system/nullable/operator!=/
---
## Nullable::operator!=(const Nullable\<T1\>\&) const method


Определяет, не равна ли величина, представленная текущим объектом, величине, представленной указанным объектом [Nullable](../).

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), с которым производится сравнение |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Константная ссылка на объект [Nullable](../), с которым производится сравнение |

### ReturnValue

True, если величина, представленная текущим объектом, не равна величине, представленной указанным объектом [Nullable](../), иначе — false

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator!=(const T1\&) const method


Определяет, не равно ли значение, представленное текущим объектом, указанному значению.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип сравниваемой величины |

| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | const T1\& | Константная ссылка на сравниваемую величину |

### ReturnValue

True, если величина, представленная текущим объектом, не равна указанной величине, иначе — false

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator!=(std::nullptr_t) const method


Определяет, не является ли значение, представленное текущим объектом, null.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### ReturnValue

True, если величина, представленная текущим объектом, не равна null, иначе — false

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
