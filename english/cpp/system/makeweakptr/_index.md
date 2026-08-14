---
title: System::MakeWeakPtr method
linktitle: MakeWeakPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::MakeWeakPtr method. Converts raw pointer to weak pointer. Overload for const pointers. Useful e. g. when using ''this'' variable in C# methods translated as const in C++.'
type: docs
weight: 26300
url: /cpp/system/makeweakptr/
---
## System::MakeWeakPtr(const X *) method


Converts raw pointer to weak pointer. Overload for const pointers. Useful e. g. when using 'this' variable in C# methods translated as const.

```cpp
template<class X> SmartPtr<X> System::MakeWeakPtr(const X *p)
```


| Parameter | Description |
| --- | --- |
| X | Pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| p | const X * | Raw pointer to object. |

### ReturnValue

Weak smart pointer to object.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeWeakPtr(X *) method


Converts raw pointer to weak pointer.

```cpp
template<class X> SmartPtr<X> System::MakeWeakPtr(X *p)
```


| Parameter | Description |
| --- | --- |
| X | Pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| p | X * | Raw pointer to object. |

### ReturnValue

Weak smart pointer to object.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
