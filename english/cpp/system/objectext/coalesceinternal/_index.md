---
title: System::ObjectExt::CoalesceInternal method
linktitle: CoalesceInternal
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::CoalesceInternal method. Implementation of ''??'' operator translation for non-nullable types. Overload for case if RT2 is convertable to RT1 in C++.'
type: docs
weight: 700
url: /cpp/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal method


Implementation of '??' operator translation for non-nullable types. Overload for case if RT2 is convertable to RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


| Parameter | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | RT1 | LHS value. |
| func | F | RHS expression. |

### ReturnValue

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
