---
title: System::BuildObject method
linktitle: BuildObject
second_title: Aspose.PDF for C++ API Reference
description: 'System::BuildObject method. Build an object with shared ownership in C++.'
type: docs
weight: 15100
url: /cpp/system/buildobject/
---
## System::BuildObject method


Build an object with shared ownership.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


| Parameter | Description |
| --- | --- |
| T | Type of object to build |
| Args | Argument types for object construction |

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Arguments to forward to object constructor |

### ReturnValue

ObjectBuilder configured for shared pointer construction
## Remarks



Creates a [SharedPtr<T>](../sharedptr/) and returns a builder for it 
[Object](../object/) construction must be finished with Get() call 

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
