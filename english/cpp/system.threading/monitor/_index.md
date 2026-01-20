---
title: System::Threading::Monitor class
linktitle: Monitor
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Monitor class. Class Monitor provides a mechanism that synchronizes access to objects in C++.'
type: docs
weight: 800
url: /cpp/system.threading/monitor/
---
## Monitor class


Class [Monitor](./) provides a mechanism that synchronizes access to objects.

```cpp
class Monitor : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [Enter](./enter/)(const SharedPtr\<Object\>\&) | Acquires an exclusive lock on a specified object. |
| static [Enter](./enter/)(const System::SharedPtr\<Object\>\&, bool\&) | Acquires an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken. |
| static [Exit](./exit/)(const SharedPtr\<Object\>\&) | Releases an exclusive lock on the specified object. |
| static [IsEntered](./isentered/)(const System::SharedPtr\<Object\>\&) | Determines whether the current thread holds the lock on the specified object. |
| static [Pulse](./pulse/)(const SharedPtr\<Object\>\&) | Notifies a thread in the waiting queue of a change in the locked object's state Not implemented. |
| static [PulseAll](./pulseall/)(const SharedPtr\<Object\>\&) | Notifies all waiting threads of a change in the object's state Not implemented. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&) | Attempts to acquire an exclusive lock on the specified object Not implemented. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, bool\&) | Attempts to acquire an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&, int32_t) | Attempts, for the specified number of milliseconds, to acquire an exclusive lock on the specified object Not implemented. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&, TimeSpan) | Attempts, for the specified amount of time, to acquire an exclusive lock on the specified object Not implemented. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, int32_t, bool\&) | Attempts, for the specified amount of time, to acquire an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) | Attempts, for the specified amount of time, to acquire an exclusive lock on the specified object, and atomically sets a value that indicates whether the lock was taken. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, int32_t, bool) | Releases the lock on an object and blocks the current thread until it reacquires the lock. If the specified time-out interval elapses, the thread enters the ready queue. Optionally exits the synchronization domain for the synchronized context before the wait and reacquires the domain afterward. Not implemented. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, TimeSpan, bool) | Releases the lock on an object and blocks the current thread until it reacquires the lock. If the specified time-out interval elapses, the thread enters the ready queue. Optionally exits the synchronization domain for the synchronized context before the wait and reacquires the domain afterward. Not implemented. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, int32_t) | Releases the lock on an object and blocks the current thread until it reacquires the lock. If the specified time-out interval elapses, the thread enters the ready queue. Not implemented. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, TimeSpan) | Releases the lock on an object and blocks the current thread until it reacquires the lock. If the specified time-out interval elapses, the thread enters the ready queue. Not implemented. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&) | Releases the lock on an object and blocks the current thread until it reacquires the lock Not implemented. |
## Remarks



```cpp
#include "system/threading/monitor.h"
#include "system/threading/thread.h"
#include "system/smart_ptr.h"
#include "system/string.h"
#include <iostream>
#include <vector>

int main()
{
  using namespace System::Threading;

  const auto threadsCount = 3;
  std::cout << "Threads count: " << threadsCount << std::endl;
  auto locker = System::MakeObject<System::Object>();
  int x = 0;

  std::vector<System::SharedPtr<Thread>> threads;
  threads.reserve(threadsCount);
  for (auto i = 0; i < threadsCount; ++i)
  {
    threads.emplace_back(System::MakeObject<Thread>([&x, &locker]() -> void {
      Monitor::Enter(locker);

      x = 1;
      for (auto i = 0; i < 5; ++i)
      {
        std::cout << Thread::get_CurrentThread()->get_Name() << ": " << x++ << std::endl;
        Thread::Sleep(100);
      }

      Monitor::Exit(locker);
    }));
    threads.back()->set_Name(System::String("Thread " + std::to_string(i)));
    threads.back()->Start();
  }

  Thread::Sleep(threadsCount * 100);

  for (auto& thread : threads)
  {
    thread->Join();
  }

  return 0;
}
/*
This code example produces the following output:
Threads count: 3
Thread 0: 1
Thread 0: 2
Thread 0: 3
Thread 0: 4
Thread 0: 5
Thread 1: 1
Thread 1: 2
Thread 1: 3
Thread 1: 4
Thread 1: 5
Thread 2: 1
Thread 2: 2
Thread 2: 3
Thread 2: 4
Thread 2: 5
*/
```

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
