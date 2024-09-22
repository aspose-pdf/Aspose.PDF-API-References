---
title: System::MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() method
linktitle: operator()
second_title: Aspose.PDF for C++ API Reference
description: 'System::MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() method. Invokes all delegates currently present in the delegates collection. Delegates are invoked in the same order as they were added to the collection. The operator blocks while the delegates are executed in C++.'
type: docs
weight: 1400
url: /cpp/system/multicastdelegate_returntype(argumenttypes...)_/operator()/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator() method


Invokes all delegates currently present in the delegates collection. Delegates are invoked in the same order as they were added to the collection. The operator blocks while the delegates are executed.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| args | ArgumentTypes... | Arguments to pass to the delegates to be invoked |

### ReturnValue

Return value of the last invoked delegate

## See Also

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
