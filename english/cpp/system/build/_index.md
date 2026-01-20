---
title: System::Build method
linktitle: Build
second_title: Aspose.PDF for C++ API Reference
description: 'System::Build method. Build an object with direct ownership in C++.'
type: docs
weight: 15000
url: /cpp/system/build/
---
## System::Build method


Build an object with direct ownership.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


| Parameter | Description |
| --- | --- |
| T | Type of object to build |
| Args | Argument types for object construction |

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Arguments to forward to object constructor |

### ReturnValue

ObjectBuilder configured for direct object construction
## Remarks



[Object](../object/) construction must be finished with [Get()](../get/) call 

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
