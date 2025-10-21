---
title: System::MakeScopeGuard method
linktitle: MakeScopeGuard
second_title: Aspose.PDF for C++ API Reference
description: 'System::MakeScopeGuard method. A factory function that creates instances of ScopedGuard class in C++.'
type: docs
weight: 23500
url: /cpp/system/makescopeguard/
---
## System::MakeScopeGuard method


A factory function that creates instances of ScopedGuard class.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


| Parameter | Description |
| --- | --- |
| The | type of the function object to be invoked by the constructed ScopedGuard object |

| Parameter | Type | Description |
| --- | --- | --- |
| f | F | The function object to pass to ScopedGuard class' constructor. |

### ReturnValue

A new instance of ScopedGuard class

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
