---
title: System::Threading::Tasks::Task::Task constructor
linktitle: Task
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::Task::Task constructor. Internal constructor for creating uninitialized tasks in C++.'
type: docs
weight: 100
url: /cpp/system.threading.tasks/task/task/
---
## Task::Task() constructor


Internal constructor for creating uninitialized tasks.

```cpp
System::Threading::Tasks::Task::Task()
```

## See Also

* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) constructor


Constructs a [Task](../) with a stateful action and state object.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


| Parameter | Type | Description |
| --- | --- | --- |
| action | const Action\<SharedPtr\<Object\>\>\& | The action to execute (accepts state object) |
| state | const SharedPtr\<Object\>\& | User-defined state object passed to the action |

## See Also

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructor


Constructs a [Task](../) with stateful action, state, and cancellation token.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


| Parameter | Type | Description |
| --- | --- | --- |
| action | const Action\<SharedPtr\<Object\>\>\& | The action to execute (accepts state object) |
| state | const SharedPtr\<Object\>\& | User-defined state object passed to the action |
| cancellationToken | const CancellationToken\& | Token to monitor for cancellation requests |

## See Also

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action<>\&) constructor


Constructs a [Task](../) with an action to execute.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


| Parameter | Type | Description |
| --- | --- | --- |
| action | const Action<>\& | The action to execute asynchronously |

## See Also

* Typedef [Action](../../../system/action/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action<>\&, const CancellationToken\&) constructor


Constructs a [Task](../) with an action and cancellation token.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


| Parameter | Type | Description |
| --- | --- | --- |
| action | const Action<>\& | The action to execute asynchronously |
| cancellationToken | const CancellationToken\& | Token to monitor for cancellation requests |

## See Also

* Typedef [Action](../../../system/action/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
