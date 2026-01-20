---
title: System::Nullable::Nullable constructor
linktitle: Nullable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable::Nullable constructor. Constructs an instance that represents null-value in C++.'
type: docs
weight: 100
url: /cpp/system/nullable/nullable/
---
## Nullable::Nullable() constructor


Constructs an instance that represents null-value.

```cpp
System::Nullable<T>::Nullable()
```

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::Nullable(const Nullable\<T1\>\&) constructor


Constructs an instance that represents a value that is represented by the specified [Nullable](../) object. The specified nullable object may represent a value of different type than the underlying type of the constructed instance in which case the represented value is converted to a value of type T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the value represented by the specified [Nullable](../) object |

## See Also

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::Nullable(const T1\&) constructor


Constructs an instance of [Nullable](../) class that represents the specified value converted (if necessary) to the value of the underlying type T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the specified value |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T1\& | A constant reference to the value to be represented by the newly constructed [Nullable](../) object |

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::Nullable(std::nullptr_t) constructor


Constructs an instance that represents null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
