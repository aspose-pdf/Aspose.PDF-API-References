---
title: System::Threading::Tasks::ResultValueTask::ResultValueTask constructor
linktitle: ResultValueTask
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultValueTask::ResultValueTask constructor. Constructs an empty, uninitialized ResultValueTask in C++.'
type: docs
weight: 100
url: /cpp/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() constructor


Constructs an empty, uninitialized [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Remarks



The task is not completed and contains no result. Attempting to get the result will throw an exception. 

## See Also

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) constructor


Constructs a [ResultValueTask](../) from a shared pointer to a [ResultTask<T>](../../resulttask/).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


| Parameter | Type | Description |
| --- | --- | --- |
| task | const RTaskPtr\<T\>\& | The task to wrap. Can be null for an empty task. |
## Remarks



The [ResultValueTask](../) will represent the state and result of the provided task. 

## See Also

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultValueTask::ResultValueTask(const T\&) constructor


Constructs a completed [ResultValueTask](../) with the specified result.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| result | const T\& | The result value to wrap in a completed task. |
## Remarks



This creates a successfully completed task that immediately returns the value. 

## See Also

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
