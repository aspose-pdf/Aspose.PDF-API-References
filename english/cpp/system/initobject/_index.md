---
title: System::InitObject method
linktitle: InitObject
second_title: Aspose.PDF for C++ API Reference
description: 'System::InitObject method. Starts initialization of an object with shared ownership in C++.'
type: docs
weight: 21800
url: /cpp/system/initobject/
---
## System::InitObject method


Starts initialization of an object with shared ownership.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```


| Parameter | Description |
| --- | --- |
| T | Type of object to initialize |

| Parameter | Type | Description |
| --- | --- | --- |
| object | const SharedPtr\<T\>\& | [Object](../object/) to initialize |

### ReturnValue

ObjectBuilder configured for shared pointer construction
## Remarks



[Object](../object/) initialization must be finished with [Get()](../get/) call 

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
