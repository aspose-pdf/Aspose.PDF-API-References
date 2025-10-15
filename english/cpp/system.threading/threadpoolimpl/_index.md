---
title: System::Threading::ThreadPoolImpl class
linktitle: ThreadPoolImpl
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::ThreadPoolImpl class. Thread pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly in C++.'
type: docs
weight: 1400
url: /cpp/system.threading/threadpoolimpl/
---
## ThreadPoolImpl class


[Thread](../thread/) pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class ThreadPoolImpl
```

## Methods

| Method | Description |
| --- | --- |
| [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Gets number of available threads. |
| static [GetInitialized](./getinitialized/)() | Gets initialization state singleton. |
| [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Gets maximal number of concurrent threads. |
| [GetMinThreads](./getminthreads/)(int\&, int\&) | Gets minimal number of threads being created by pool. |
| [JoinAll](./joinall/)() | Joins all owned threads. Waits infinitely. |
| [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback, const System::SharedPtr\<System::Object\>\&) | Adds work item to queue. |
| [SetMaxThreads](./setmaxthreads/)(int, int) | Sets number of threads owned by pool. |
| [SetMinThreads](./setminthreads/)(int, int) | Sets minimal number of threads owned by pool. |
| [ThreadPoolImpl](./threadpoolimpl/)() | Constructor. |
| [~ThreadPoolImpl](./~threadpoolimpl/)() | Destructor. Joins all threads if they were not terminated yet. |
## See Also

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
