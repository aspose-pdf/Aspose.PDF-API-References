---
title: System::ObjectExt::CoalesceAssign method
linktitle: CoalesceAssign
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::CoalesceAssign method. Implementation of ''??='' operator translation in C++.'
type: docs
weight: 600
url: /cpp/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign method


Implementation of '??=' operator translation.

```cpp
template<typename T0,typename T1> static T0 & System::ObjectExt::CoalesceAssign(T0 &value, T1 func)
```


| Parameter | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | T0\& | LHS value. |
| func | T1 | RHS expression. |

### ReturnValue

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
