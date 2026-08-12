---
title: "System::Threading::ThreadPool class"
linktitle: "ThreadPool"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::ThreadPool class. Trådpools‑API som möjliggör att skjuta jobb till en kö som läses av en pool av arbetstrådar. Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 1300
url: /sv/cpp/system.threading/threadpool/
---
## ThreadPool class


[Thread](../thread/) pool API allowing it pushing jobs into queue to be read by pool of worker threads. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ThreadPool : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Hämtar antalet tillgängliga trådar. |
| static [GetInstance](./getinstance/)() | RTTI-information. |
| static [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Hämtar maximalt antal samtidiga trådar. |
| static [GetMinThreads](./getminthreads/)(int\&, int\&) | Hämtar minimalt antal trådar som skapas av poolen. |
| static [JoinAllThreads](./joinallthreads/)() | Joinar alla ägda trådar. Väntar oändligt. |
| [operator=](./operator=/)(const ThreadPool\&) | Ingen kopiering. |
| static [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback) | Lägger till ett arbetsobjekt i kön som finns med en callback utan parametrar. |
| static [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback, const System::SharedPtr\<System::Object\>\&) | Lägger till ett arbetsobjekt i kön som finns med en callback utan parametrar. |
| static [SetMaxThreads](./setmaxthreads/)(int, int) | Ställer in antalet trådar som ägs av poolen. |
| static [SetMinThreads](./setminthreads/)(int, int) | Ställer in minimalt antal trådar som ägs av poolen. |
| [ThreadPool](./threadpool/)(const ThreadPool\&) | Ingen kopiering. |
## Anmärkningar



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

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
