---
title: System::Threading::Tasks::ValueTask class
linktitle: ValueTask
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ValueTask class. Provides an awaitable result of an asynchronous operation in C++.'
type: docs
weight: 500
url: /cpp/system.threading.tasks/valuetask/
---
## ValueTask class


Provides an awaitable result of an asynchronous operation.

```cpp
class ValueTask : public System::IEquatable<ValueTask>,
                  public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| [AsTask](./astask/)() const | Converts this [ValueTask](./) to a shared pointer to [Task](../task/). |
| [ConfigureAwait](./configureawait/)(bool) const | Configures an awaiter for this task. |
| [Equals](./equals/)(ValueTask) override | Determines whether this instance equals another [ValueTask](./) instance. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determines whether this instance equals another object. |
| [get_IsCanceled](./get_iscanceled/)() const | Gets a value indicating whether the task completed due to being canceled. |
| [get_IsCompleted](./get_iscompleted/)() const | Gets a value indicating whether the task has completed. |
| [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Gets a value indicating whether the task completed successfully. |
| [get_IsFaulted](./get_isfaulted/)() const | Gets a value indicating whether the task completed due to an unhandled exception. |
| [GetAwaiter](./getawaiter/)() const | Gets an awaiter for this task to support await expressions. |
| [operator!=](./operator!=/)(const ValueTask\&) const | Inequality operator for [ValueTask](./). |
| [operator==](./operator==/)(const ValueTask\&) const | Equality operator for [ValueTask](./). |
| [ValueTask](./valuetask/)() | Constructs an empty, uninitialized [ValueTask](./). |
| [ValueTask](./valuetask/)(const TaskPtr\&) | Constructs a [ValueTask](./) from a shared pointer to a [Task](../task/). |
## See Also

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
