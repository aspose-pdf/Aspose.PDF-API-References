---
title: System::Threading::Thread class
linktitle: Thread
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Thread class. Thread implementation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.threading/thread/
---
## Thread class


[Thread](./) implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Thread : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Abort](./abort/)() | Aborts thread. Not implemented. |
| [get_CurrentCulture](./get_currentculture/)() | Gets thread culture. |
| static [get_CurrentThread](./get_currentthread/)() | Gets object which describes current thread. |
| [get_CurrentUICulture](./get_currentuiculture/)() | Gets user interface culture used by thread. |
| [get_IsAlive](./get_isalive/)() | Checks whether thread is alive. |
| [get_IsBackground](./get_isbackground/)() | Checks whether thread is background. |
| [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | Checks if thread is owned by a thread pool. |
| [get_ManagedThreadId](./get_managedthreadid/)() const | Gets identifier of thread. Can be got from OS, but if OS thread identifier exceeds int limits, ids of threads can intersect. |
| [get_Name](./get_name/)() | Gets thread name. |
| [get_ThreadState](./get_threadstate/)() | Gets thread state. |
| static [GetCurrentThreadId](./getcurrentthreadid/)() | Gets identifier of current thread. |
| [GetHashCode](./gethashcode/)() const override |  |
| [Interrupt](./interrupt/)() | Interrupt thread. Not implemented. |
| [Join](./join/)() | Joins managed thread. Performs unlimited waiting if required. |
| [Join](./join/)(int) | Joins managed thread. Performs limited waiting. |
| [Join](./join/)(TimeSpan) | Joins managed thread. Performs limited waiting. |
| static [MemoryBarrier](./memorybarrier/)() | Synchronizes memory access. |
| [operator=](./operator=/)(const Thread\&) | Copies TLS data from different thread. |
| [set_CurrentCulture](./set_currentculture/)(const SharedPtr\<Globalization::CultureInfo\>\&) | Sets thread culture. |
| [set_CurrentUICulture](./set_currentuiculture/)(const SharedPtr\<Globalization::CultureInfo\>\&) | Sets user interface culture used by thread. |
| [set_IsBackground](./set_isbackground/)(bool) | Sets thread to background or foreground. |
| [set_Name](./set_name/)(const System::String\&) | Sets thread name. |
| static [Sleep](./sleep/)(int) | Stops current thread for specified timeout. |
| static [Sleep](./sleep/)(TimeSpan) | Stops current thread for specified timeout. |
| static [SpinWait](./spinwait/)(int) | Waits for specific number of loop iterations. |
| [Start](./start/)() | Starts thread using null argument object. |
| [Start](./start/)(const System::SharedPtr\<System::Object\>\&) | Starts thread. |
| [Thread](./thread/)() | Constructor. |
| [Thread](./thread/)(ThreadStart) | Constructor. |
| [Thread](./thread/)(ParameterizedThreadStart) | Constructor. |
| [Thread](./thread/)(Thread\&) | Copy constructor. |
| static [Yield](./yield/)() | Yields thread. |
| virtual [~Thread](./~thread/)() | Destructor. |
## Remarks



```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
This code example produces the following output:
Main thread ID: 2
Child thread ID: 1
*/
```

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
