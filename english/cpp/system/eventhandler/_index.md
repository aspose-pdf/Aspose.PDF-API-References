---
title: System::EventHandler typedef
linktitle: EventHandler
second_title: Aspose.PDF for C++ API Reference
description: 'System::EventHandler typedef. Represents a method that reacts to and processes an event. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 11500
url: /cpp/system/eventhandler/
---
## EventHandler typedef


Represents a method that reacts to and processes an event. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
using System::EventHandler =  MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
