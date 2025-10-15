---
title: System::MakeSharedPtr method
linktitle: MakeSharedPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::MakeSharedPtr method. Converts raw pointer to smart pointer. Overload for const pointers. Useful e. g. when using ''this'' variable in C# methods translated as const in C++.'
type: docs
weight: 23600
url: /cpp/system/makesharedptr/
---
## System::MakeSharedPtr(const X *) method


Converts raw pointer to smart pointer. Overload for const pointers. Useful e. g. when using 'this' variable in C# methods translated as const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


| Parameter | Description |
| --- | --- |
| X | Pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| p | const X * | Raw pointer to object. |

### ReturnValue

Shared smart pointer to object.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeSharedPtr(X *) method


Converts raw pointer to smart pointer.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


| Parameter | Description |
| --- | --- |
| X | Pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| p | X * | Raw pointer to object. |

### ReturnValue

Shared smart pointer to object.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
