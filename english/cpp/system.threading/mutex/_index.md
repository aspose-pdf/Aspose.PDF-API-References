---
title: System::Threading::Mutex class
linktitle: Mutex
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Mutex class. Mutex implemnetation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.threading/mutex/
---
## Mutex class


[Mutex](./) implemnetation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Mutex : public System::Threading::WaitHandle
```

## Methods

| Method | Description |
| --- | --- |
| [Mutex](./mutex/)() | RTTI information. |
| [Mutex](./mutex/)(bool) | Constructor. |
| [Mutex](./mutex/)(bool, const String\&) | Constructor. |
| [ReleaseMutex](./releasemutex/)() | Releases the mutex. |
| static [Remove](./remove/)(const String\&) | Erases a named mutex from the system. |
| virtual [Reset](./reset/)() | Resets mutex state. Not implemented. |
| virtual [Set](./set/)() | Set mutex to signalled state. Not implemented. |
| [WaitOne](./waitone/)() override | Locks mutex. Performs unlimited waiting if neccessary. |
| [WaitOne](./waitone/)(int) override | Locks mutex. Performs waiting if neccessary. |
| [WaitOne](./waitone/)(TimeSpan) override | Locks mutex. Performs waiting if neccessary. |
## Fields

| Field | Description |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Special value to be returned by the function otherwise returning index of signalled object in array, if timeout exceeds and nothing signals. |
## Remarks



```cpp
#include "system/threading/mutex.h"
#include "system/threading/thread.h"
#include "system/console.h"
#include "system/convert.h"
#include "system/smart_ptr.h"
#include "system/string.h"

int main()
{
  auto mutex = System::MakeObject<System::Threading::Mutex>();

  System::String str;

  const int THREADS_COUNT = 3;
  std::vector<System::SharedPtr<System::Threading::Thread>> threads;
  threads.reserve(THREADS_COUNT);

  for (auto i = 0; i < THREADS_COUNT; ++i)
  {
    threads.push_back(System::MakeObject<System::Threading::Thread>([&mutex, &str]()
    {
      mutex->WaitOne();

      str += u"Thread " + System::Convert::ToString(System::Threading::Thread::GetCurrentThreadId()) + u" started." + System::Environment::get_NewLine();

      System::Threading::Thread::Sleep(200);

      str += u"Thread " + System::Convert::ToString(System::Threading::Thread::GetCurrentThreadId()) + u" ended." + System::Environment::get_NewLine();

      mutex->ReleaseMutex();
    }));

    threads[i]->Start();
  }

  System::Threading::Thread::Sleep(700);

  System::Console::WriteLine(str);

  return 0;
}
/*
This code example produces the following output:
Thread 1 started.
Thread 1 ended.
Thread 2 started.
Thread 2 ended.
Thread 3 started.
Thread 3 ended.
*/
```

## See Also

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
