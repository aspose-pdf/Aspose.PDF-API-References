---
title: System::Cast method
linktitle: Cast
second_title: Aspose.PDF for C++ API Reference
description: 'System::Cast method. Performs cast on SmartPtr objects in C++.'
type: docs
weight: 15200
url: /cpp/system/cast/
---
## System::Cast method


Performs cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Source pointer. |

### ReturnValue

Cast result if cast is allowed.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
