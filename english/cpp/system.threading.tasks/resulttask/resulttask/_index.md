---
title: System::Threading::Tasks::ResultTask::ResultTask constructor
linktitle: ResultTask
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultTask::ResultTask constructor. Internal implementation. Not for user code in C++.'
type: docs
weight: 100
url: /cpp/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask() constructor


Internal implementation. Not for user code.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Remarks


Internal constructor for creating uninitialized result tasks 
## See Also

* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ResultTask(const Func\<T\>\&) constructor


Constructs a [ResultTask](../) with a function that returns a value.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


| Parameter | Type | Description |
| --- | --- | --- |
| function | const Func\<T\>\& | The function to execute asynchronously that returns a result |

## See Also

* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ResultTask(const T\&) constructor


Internal constructor for creating result tasks with specified result.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## See Also

* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
