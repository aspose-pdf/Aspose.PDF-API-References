---
title: "System::Nullable::operator-= метод"
linktitle: "operator-="
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Nullable::operator-= метод. Применяет operator-=() к значению, представленному текущим объектом, используя значение, представленное указанным объектом Nullable, в качестве правого аргумента в C++."
type: docs
weight: 1500
url: /ru/cpp/system/nullable/operator-=/
---
## Nullable::operator-=(const Nullable\<T1\>\&) method


Применяет [operator-=()](./) к значению, представленному текущим объектом, используя значение, представленное указанным объектом [Nullable](../), в качестве правого аргумента.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), значение которого используется в качестве правого аргумента [operator-=()](./) |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Константная ссылка на объект [Nullable](../), значение которого используется в качестве правого аргумента [operator-=()](./), применяемого к значению, представленному текущим объектом. |

### ReturnValue

Ссылка на себя

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-=(const T1\&) method


Применяет [operator-=()](./) к значению, представленному текущим объектом, используя указанное значение в качестве правого аргумента.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип значения, используемого в качестве правого аргумента [operator-=()](./) |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const T1\& | Константная ссылка на значение, используемое в качестве правого аргумента [operator-=()](./), применяемого к значению, представленному текущим объектом. |

### ReturnValue

Ссылка на себя

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-=(T1) method


Возвращает экземпляр класса [Nullable](../), представляющий нулевое значение.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
