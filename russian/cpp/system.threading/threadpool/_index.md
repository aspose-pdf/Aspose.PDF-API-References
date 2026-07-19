---
title: "System::Threading::ThreadPool class"
linktitle: "ThreadPool"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::ThreadPool class. API пула потоков, позволяющее помещать задания в очередь для обработки пулом рабочих потоков. Это статический тип без экземплярных сервисов. Вам никогда не следует создавать его экземпляры каким-либо способом в C++."
type: docs
weight: 1300
url: /ru/cpp/system.threading/threadpool/
---
## ThreadPool class


[Thread](../thread/) pool API allowing it pushing jobs into queue to be read by pool of worker threads. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ThreadPool : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Получает количество доступных потоков. |
| static [GetInstance](./getinstance/)() | Информация RTTI. |
| static [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Получает максимальное количество одновременно работающих потоков. |
| static [GetMinThreads](./getminthreads/)(int\&, int\&) | Получает минимальное количество потоков, создаваемых пулом. |
| static [JoinAllThreads](./joinallthreads/)() | Ожидает завершения всех принадлежащих потоков. Ожидание без ограничения времени. |
| [operator=](./operator=/)(const ThreadPool\&) | Копирование не допускается. |
| static [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback) | Помещает элемент работы в очередь, где присутствует обратный вызов без параметров. |
| static [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback, const System::SharedPtr\<System::Object\>\&) | Помещает элемент работы в очередь, где присутствует обратный вызов без параметров. |
| static [SetMaxThreads](./setmaxthreads/)(int, int) | Устанавливает количество потоков, принадлежащих пулу. |
| static [SetMinThreads](./setminthreads/)(int, int) | Устанавливает минимальное количество потоков, принадлежащих пулу. |
| [ThreadPool](./threadpool/)(const ThreadPool\&) | Копирование не допускается. |
## Примечания



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

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
