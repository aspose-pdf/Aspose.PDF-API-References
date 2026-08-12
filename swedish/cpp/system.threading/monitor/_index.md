---
title: "System::Threading::Monitor klass"
linktitle: "Monitor"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Monitor-klass. Klassen Monitor tillhandahåller en mekanism som synkroniserar åtkomst till objekt i C++."
type: docs
weight: 800
url: /sv/cpp/system.threading/monitor/
---
## Monitor class


Klassen [Monitor](./) tillhandahåller en mekanism som synkroniserar åtkomst till objekt.

```cpp
class Monitor : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Enter](./enter/)(const SharedPtr\<Object\>\&) | Erhåller ett exklusivt lås på ett specificerat objekt. |
| static [Enter](./enter/)(const System::SharedPtr\<Object\>\&, bool\&) | Erhåller ett exklusivt lås på det specificerade objektet och sätter atomärt ett värde som indikerar om låset togs. |
| static [Exit](./exit/)(const SharedPtr\<Object\>\&) | Frigör ett exklusivt lås på det specificerade objektet. |
| static [IsEntered](./isentered/)(const System::SharedPtr\<Object\>\&) | Bestämmer om den aktuella tråden håller låset på det specificerade objektet. |
| static [Pulse](./pulse/)(const SharedPtr\<Object\>\&) | Meddelar en tråd i väntekön om en förändring i det låsta objektets tillstånd. Ej implementerad. |
| static [PulseAll](./pulseall/)(const SharedPtr\<Object\>\&) | Meddelar alla väntande trådar om en förändring i objektets tillstånd. Ej implementerad. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&) | Försöker erhålla ett exklusivt lås på det specificerade objektet. Ej implementerad. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, bool\&) | Försöker erhålla ett exklusivt lås på det specificerade objektet och sätter atomärt ett värde som indikerar om låset togs. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&, int32_t) | Försöker, under det specificerade antalet millisekunder, erhålla ett exklusivt lås på det specificerade objektet. Ej implementerad. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&, TimeSpan) | Försöker, under den specificerade tidsperioden, erhålla ett exklusivt lås på det specificerade objektet. Ej implementerad. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, int32_t, bool\&) | Försöker, under den specificerade tidsperioden, erhålla ett exklusivt lås på det specificerade objektet och sätter atomärt ett värde som indikerar om låset togs. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) | Försöker, under den specificerade tidsperioden, erhålla ett exklusivt lås på det specificerade objektet och sätter atomärt ett värde som indikerar om låset togs. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, int32_t, bool) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om den specificerade tidsgränsen löper ut går tråden in i körkön. Eventuellt lämnar den synkroniseringsdomänen för det synkroniserade sammanhanget före väntan och återfår domänen efteråt. Ej implementerad. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, TimeSpan, bool) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om den specificerade tidsgränsen löper ut går tråden in i körkön. Eventuellt lämnar den synkroniseringsdomänen för det synkroniserade sammanhanget före väntan och återfår domänen efteråt. Ej implementerad. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, int32_t) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om den specificerade tidsgränsen löper ut går tråden in i körkön. Ej implementerad. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, TimeSpan) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om den specificerade tidsgränsen löper ut går tråden in i körkön. Ej implementerad. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Ej implementerad. |
## Anmärkningar



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

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
