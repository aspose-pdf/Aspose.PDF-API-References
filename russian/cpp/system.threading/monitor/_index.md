---
title: "Класс System::Threading::Monitor"
linktitle: "Monitor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Threading::Monitor. Класс Monitor предоставляет механизм, синхронизирующий доступ к объектам в C++."
type: docs
weight: 800
url: /ru/cpp/system.threading/monitor/
---
## Monitor class


Класс [Monitor](./) предоставляет механизм, синхронизирующий доступ к объектам.

```cpp
class Monitor : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Enter](./enter/)(const SharedPtr\<Object\>\&) | Получает эксклюзивную блокировку указанного объекта. |
| static [Enter](./enter/)(const System::SharedPtr\<Object\>\&, bool\&) | Получает эксклюзивную блокировку указанного объекта и атомарно устанавливает значение, указывающее, была ли блокировка получена. |
| static [Exit](./exit/)(const SharedPtr\<Object\>\&) | Снимает эксклюзивную блокировку с указанного объекта. |
| static [IsEntered](./isentered/)(const System::SharedPtr\<Object\>\&) | Определяет, удерживает ли текущий поток блокировку указанного объекта. |
| static [Pulse](./pulse/)(const SharedPtr\<Object\>\&) | Уведомляет поток в очереди ожидания об изменении состояния заблокированного объекта. Не реализовано. |
| static [PulseAll](./pulseall/)(const SharedPtr\<Object\>\&) | Уведомляет все ожидающие потоки об изменении состояния объекта. Не реализовано. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&) | Пытается получить эксклюзивную блокировку указанного объекта. Не реализовано. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, bool\&) | Пытается получить эксклюзивную блокировку указанного объекта и атомарно устанавливает значение, указывающее, была ли блокировка получена. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&, int32_t) | Пытается в течение указанного количества миллисекунд получить эксклюзивную блокировку указанного объекта. Не реализовано. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&, TimeSpan) | Пытается в течение указанного периода времени получить эксклюзивную блокировку указанного объекта. Не реализовано. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, int32_t, bool\&) | Пытается в течение указанного периода времени получить эксклюзивную блокировку указанного объекта и атомарно устанавливает значение, указывающее, была ли блокировка получена. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) | Пытается в течение указанного периода времени получить эксклюзивную блокировку указанного объекта и атомарно устанавливает значение, указывающее, была ли блокировка получена. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, int32_t, bool) | Снимает блокировку с объекта и блокирует текущий поток до тех пор, пока он не получит блокировку снова. Если указанный интервал тайм‑аута истекает, поток переходит в очередь готовности. При необходимости выходит из домена синхронизации для синхронизированного контекста перед ожиданием и повторно входит в домен после него. Не реализовано. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, TimeSpan, bool) | Снимает блокировку с объекта и блокирует текущий поток до тех пор, пока он не получит блокировку снова. Если указанный интервал тайм‑аута истекает, поток переходит в очередь готовности. При необходимости выходит из домена синхронизации для синхронизированного контекста перед ожиданием и повторно входит в домен после него. Не реализовано. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, int32_t) | Снимает блокировку с объекта и блокирует текущий поток до тех пор, пока он не получит блокировку снова. Если указанный интервал тайм‑аута истекает, поток переходит в очередь готовности. Не реализовано. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, TimeSpan) | Снимает блокировку с объекта и блокирует текущий поток до тех пор, пока он не получит блокировку снова. Если указанный интервал тайм‑аута истекает, поток переходит в очередь готовности. Не реализовано. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&) | Снимает блокировку с объекта и блокирует текущий поток до тех пор, пока он не получит блокировку снова. Не реализовано. |
## Примечания



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

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
