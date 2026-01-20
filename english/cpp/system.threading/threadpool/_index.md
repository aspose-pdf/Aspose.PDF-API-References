---
title: System::Threading::ThreadPool class
linktitle: ThreadPool
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::ThreadPool class. Thread pool API allowing it pushing jobs into queue to be read by pool of worker threads. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 1300
url: /cpp/system.threading/threadpool/
---
## ThreadPool class


[Thread](../thread/) pool API allowing it pushing jobs into queue to be read by pool of worker threads. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ThreadPool : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Gets number of available threads. |
| static [GetInstance](./getinstance/)() | RTTI information. |
| static [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Gets maximal number of concurrent threads. |
| static [GetMinThreads](./getminthreads/)(int\&, int\&) | Gets minimal number of threads being created by pool. |
| static [JoinAllThreads](./joinallthreads/)() | Joins all owned threads. Waits infinitely. |
| [operator=](./operator=/)(const ThreadPool\&) | No copying. |
| static [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback) | Puts work item into queue which is present with callback with no parameter. |
| static [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback, const System::SharedPtr\<System::Object\>\&) | Puts work item into queue which is present with callback with no parameter. |
| static [SetMaxThreads](./setmaxthreads/)(int, int) | Sets number of threads owned by pool. |
| static [SetMinThreads](./setminthreads/)(int, int) | Sets minimal number of threads owned by pool. |
| [ThreadPool](./threadpool/)(const ThreadPool\&) | No copying. |
## Remarks



```cpp
#include "system/threading/thread_pool.h"
#include "system/threading/thread.h"
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>
#include <mutex>
#include <string>
#include <thread>

const std::string &BooleanToString(bool value)
{
  static const std::string True = "True";
  static const std::string False = "False";

  return value ? True : False;
}

int main()
{
  using namespace System::Threading;
  std::mutex m;

  const auto threadsCount = std::thread::hardware_concurrency();

  for (unsigned int i = 0; i < threadsCount; ++i)
  {
    ThreadPool::QueueUserWorkItem([&m](System::SharedPtr<System::Object> object) -> void {
      auto thread = Thread::get_CurrentThread();
      m.lock();
      std::cout << "Background: " << BooleanToString(thread->get_IsBackground()) <<
        ", Thread pool: " << BooleanToString(thread->get_IsThreadPoolThread()) <<
        ", Thread ID: " << thread->get_ManagedThreadId() << std::endl;
      m.unlock();
    });
  }

  ThreadPool::JoinAllThreads();

  return 0;
}
/*
This code example produces the following output:
Background: True, Thread pool: True, Thread ID: 1
Background: True, Thread pool: True, Thread ID: 3
Background: True, Thread pool: True, Thread ID: 5
Background: True, Thread pool: True, Thread ID: 6
Background: True, Thread pool: True, Thread ID: 9
Background: True, Thread pool: True, Thread ID: 1
Background: True, Thread pool: True, Thread ID: 7
Background: True, Thread pool: True, Thread ID: 2
Background: True, Thread pool: True, Thread ID: 4
Background: True, Thread pool: True, Thread ID: 3
Background: True, Thread pool: True, Thread ID: 12
Background: True, Thread pool: True, Thread ID: 8
Background: True, Thread pool: True, Thread ID: 5
Background: True, Thread pool: True, Thread ID: 6
Background: True, Thread pool: True, Thread ID: 16
Background: True, Thread pool: True, Thread ID: 11
*/
```

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
