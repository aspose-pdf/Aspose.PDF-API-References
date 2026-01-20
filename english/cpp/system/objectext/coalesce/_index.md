---
title: System::ObjectExt::Coalesce method
linktitle: Coalesce
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::Coalesce method. Implementation of ''??'' operator translation for nullable types in C++.'
type: docs
weight: 500
url: /cpp/system/objectext/coalesce/
---
## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) method


Implementation of '??' operator translation for nullable types.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```


| Parameter | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | System::Nullable\<T0\> | LHS value. |
| func | T1 | RHS expression. |

### ReturnValue

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## See Also

* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Coalesce(T0, T1) method


Implementation of '??' operator translation for non-nullable types.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```


| Parameter | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | T0 | LHS value. |
| func | T1 | RHS expression. |

### ReturnValue

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
