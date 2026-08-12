---
title: "System::Threading::Mutex class"
linktitle: "Mutex"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Mutex class. Mutex-implementation. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.threading/mutex/
---
## Mutex class


[Mutex](./) implemnetation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Mutex : public System::Threading::WaitHandle
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Mutex](./mutex/)() | RTTI-information. |
| [Mutex](./mutex/)(bool) | Konstruktor. |
| [Mutex](./mutex/)(bool, const String\&) | Konstruktor. |
| [ReleaseMutex](./releasemutex/)() | Frigör mutexen. |
| static [Remove](./remove/)(const String\&) | Raderar en namngiven mutex från systemet. |
| virtual [Reset](./reset/)() | Återställer mutexens tillstånd. Ej implementerat. |
| virtual [Set](./set/)() | Sätter mutexen till signalerat tillstånd. Ej implementerat. |
| [WaitOne](./waitone/)() override | Låser mutexen. Utför obegränsad väntan om nödvändigt. |
| [WaitOne](./waitone/)(int) override | Låser mutexen. Utför väntan om nödvändigt. |
| [WaitOne](./waitone/)(TimeSpan) override | Låser mutexen. Utför väntan om nödvändigt. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Speciellt värde som ska returneras av funktionen annars returneras index för signaliserat objekt i arrayen, om tidsgränsen överskrids och inget signalerar. |
## Anmärkningar



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

## Se även

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
