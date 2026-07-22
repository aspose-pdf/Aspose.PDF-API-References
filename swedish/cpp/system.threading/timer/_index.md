---
title: "System::Threading::Timer class"
linktitle: "Timer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Timer class. Timer‑klass som kör ett jobb i en separat tråd efter en fördröjning. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1500
url: /sv/cpp/system.threading/timer/
---
## Timer class


[Timer](./) class that executes job item in separate thread after delay. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Timer : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Change](./change/)(int64_t, int64_t) | Schemalägger om eller avbryter timern. |
| [Change](./change/)(System::TimeSpan, System::TimeSpan) | Schemalägger om eller avbryter timern. |
| [Dispose](./dispose/)() | Avplanerar timern. |
| [Timer](./timer/)(TimerCallback) | Konstruktor. |
| [Timer](./timer/)(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) | Konstruktor. |
| [Timer](./timer/)(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) | Konstruktor. |
## Anmärkningar



```cpp
#include "system/threading/thread.h"
#include "system/threading/timer.h"
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  using namespace System::Threading;

  auto number = 0;
  auto timer = System::MakeObject<Timer>([&number](System::SharedPtr<System::Object> object) -> void {
    std::cout << ++number << std::endl;
  }, nullptr, 0, 200);

  Thread::Sleep(1000);
  timer->Dispose();

  return 0;
}
/*
This code example produces the following output:
1
2
3
4
5
*/
```

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
