---
title: "System::Threading::ThreadPool class"
linktitle: "ThreadPool"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::ThreadPool class. API de pool de hilos que permite insertar trabajos en la cola para ser leídos por un conjunto de hilos de trabajo. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio en C++."
type: docs
weight: 1300
url: /es/cpp/system.threading/threadpool/
---
## ThreadPool class


[Thread](../thread/) pool API allowing it pushing jobs into queue to be read by pool of worker threads. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ThreadPool : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Obtiene el número de hilos disponibles. |
| static [GetInstance](./getinstance/)() | Información RTTI. |
| static [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Obtiene el número máximo de hilos concurrentes. |
| static [GetMinThreads](./getminthreads/)(int\&, int\&) | Obtiene el número mínimo de hilos creados por el pool. |
| static [JoinAllThreads](./joinallthreads/)() | Une todos los hilos propios. Espera indefinidamente. |
| [operator=](./operator=/)(const ThreadPool\&) | Sin copia. |
| static [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback) | Coloca el elemento de trabajo en la cola que está presente con una devolución de llamada sin parámetros. |
| static [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback, const System::SharedPtr\<System::Object\>\&) | Coloca el elemento de trabajo en la cola que está presente con una devolución de llamada sin parámetros. |
| static [SetMaxThreads](./setmaxthreads/)(int, int) | Establece el número de hilos propiedad del pool. |
| static [SetMinThreads](./setminthreads/)(int, int) | Establece el número mínimo de hilos propiedad del pool. |
| [ThreadPool](./threadpool/)(const ThreadPool\&) | Sin copia. |
## Observaciones



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

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
