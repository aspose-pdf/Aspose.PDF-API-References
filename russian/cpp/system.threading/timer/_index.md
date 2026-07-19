---
title: "System::Threading::Timer class"
linktitle: "Timer"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Timer class. Класс таймера, который выполняет задание в отдельном потоке после задержки. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1500
url: /ru/cpp/system.threading/timer/
---
## Timer class


[Timer](./) class that executes job item in separate thread after delay. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Timer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Change](./change/)(int64_t, int64_t) | Перепланирует или отменяет таймер. |
| [Change](./change/)(System::TimeSpan, System::TimeSpan) | Перепланирует или отменяет таймер. |
| [Dispose](./dispose/)() | Отменяет планирование таймера. |
| [Timer](./timer/)(TimerCallback) | Конструктор. |
| [Timer](./timer/)(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) | Конструктор. |
| [Timer](./timer/)(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) | Конструктор. |
## Примечания



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

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
