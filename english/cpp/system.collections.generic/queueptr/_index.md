---
title: System::Collections::Generic::QueuePtr class
linktitle: QueuePtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::QueuePtr class. Queue pointer. This type is a pointer to manage other object''s deletion. It should be allocated on stack and passed to functions either by value or by const reference in C++.'
type: docs
weight: 3700
url: /cpp/system.collections.generic/queueptr/
---
## QueuePtr class


[Queue](../queue/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<T0>
```

## Methods

| Method | Description |
| --- | --- |
| [QueuePtr](./queueptr/)() | Constructs null pointer. |
| [QueuePtr](./queueptr/)(const SharedPtr\<Queue\<T\>\>\&) | Constructs pointer to specific queue. |

## See Also

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
