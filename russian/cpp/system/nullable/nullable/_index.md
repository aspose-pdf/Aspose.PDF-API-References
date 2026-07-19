---
title: "System::Nullable::Nullable constructor"
linktitle: "Nullable"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Nullable::Nullable constructor. Создаёт экземпляр, представляющий null-значение в C++."
type: docs
weight: 100
url: /ru/cpp/system/nullable/nullable/
---
## Nullable::Nullable() constructor


Создаёт экземпляр, представляющий значение null.

```cpp
System::Nullable<T>::Nullable()
```

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::Nullable(const Nullable\<T1\>\&) constructor


Создаёт экземпляр, представляющий значение, которое представлено указанным объектом [Nullable](../). Указанный nullable‑объект может представлять значение другого типа, отличного от базового типа создаваемого экземпляра, в этом случае представленное значение преобразуется к типу T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип значения, представленного указанным объектом [Nullable](../) |

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::Nullable(const T1\&) constructor


Создаёт экземпляр класса [Nullable](../), представляющий указанное значение, преобразованное (при необходимости) к значению базового типа T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип указанного значения |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T1\& | Константная ссылка на значение, которое будет представлено вновь созданным объектом [Nullable](../) |

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::Nullable(std::nullptr_t) constructor


Создаёт экземпляр, представляющий null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
