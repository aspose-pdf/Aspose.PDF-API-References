---
title: System::BuildArray method
linktitle: BuildArray
second_title: Aspose.PDF for C++ API Reference
description: 'System::BuildArray method. Build an array in C++.'
type: docs
weight: 15100
url: /cpp/system/buildarray/
---
## System::BuildArray method


Build an array.

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```


| Parameter | Description |
| --- | --- |
| T | Element type of array to build |

### ReturnValue

ObjectBuilder configured for array construction
## Remarks



Creates a [ArrayPtr<T>](../arrayptr/) and returns a builder for it 
[Object](../object/) construction must be finished with [Get()](../get/) call 

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
