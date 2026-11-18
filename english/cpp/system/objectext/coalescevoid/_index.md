---
title: System::ObjectExt::CoalesceVoid method
linktitle: CoalesceVoid
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::CoalesceVoid method. Implementation of ''??'' operator in case when right part returns void (it throws, for example) in C++.'
type: docs
weight: 800
url: /cpp/system/objectext/coalescevoid/
---
## ObjectExt::CoalesceVoid method


Implementation of '??' operator in case when right part returns void (it throws, for example).

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::CoalesceVoid(T0 value, T1 func)
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

Executes func when value is nullptr and returns value.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
