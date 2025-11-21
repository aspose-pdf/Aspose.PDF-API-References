---
title: System::ForceStaticCast method
linktitle: ForceStaticCast
second_title: Aspose.PDF for C++ API Reference
description: 'System::ForceStaticCast method. Performs real static cast on SmartPtr objects in C++.'
type: docs
weight: 20400
url: /cpp/system/forcestaticcast/
---
## System::ForceStaticCast method


Performs real static cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Source pointer. |

### ReturnValue

Cast result if cast is allowed, otherwise the behavior is undefined.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
