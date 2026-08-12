---
title: "Clase System::Threading::Monitor"
linktitle: "Monitor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::Monitor. La clase Monitor proporciona un mecanismo que sincroniza el acceso a objetos en C++."
type: docs
weight: 800
url: /es/cpp/system.threading/monitor/
---
## Monitor class


La clase [Monitor](./) proporciona un mecanismo que sincroniza el acceso a objetos.

```cpp
class Monitor : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Enter](./enter/)(const SharedPtr\<Object\>\&) | Adquiere un bloqueo exclusivo en un objeto especificado. |
| static [Enter](./enter/)(const System::SharedPtr\<Object\>\&, bool\&) | Adquiere un bloqueo exclusivo en el objeto especificado y establece de forma atómica un valor que indica si el bloqueo fue tomado. |
| static [Exit](./exit/)(const SharedPtr\<Object\>\&) | Libera un bloqueo exclusivo en el objeto especificado. |
| static [IsEntered](./isentered/)(const System::SharedPtr\<Object\>\&) | Determina si el hilo actual posee el bloqueo en el objeto especificado. |
| static [Pulse](./pulse/)(const SharedPtr\<Object\>\&) | Notifica a un hilo en la cola de espera un cambio en el estado del objeto bloqueado No implementado. |
| static [PulseAll](./pulseall/)(const SharedPtr\<Object\>\&) | Notifica a todos los hilos en espera un cambio en el estado del objeto No implementado. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&) | Intenta adquirir un bloqueo exclusivo en el objeto especificado No implementado. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, bool\&) | Intenta adquirir un bloqueo exclusivo en el objeto especificado y establece de forma atómica un valor que indica si el bloqueo fue tomado. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&, int32_t) | Intenta, durante el número especificado de milisegundos, adquirir un bloqueo exclusivo en el objeto especificado No implementado. |
| static [TryEnter](./tryenter/)(const SharedPtr\<Object\>\&, TimeSpan) | Intenta, durante la cantidad de tiempo especificada, adquirir un bloqueo exclusivo en el objeto especificado No implementado. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, int32_t, bool\&) | Intenta, durante la cantidad de tiempo especificada, adquirir un bloqueo exclusivo en el objeto especificado y establece de forma atómica un valor que indica si el bloqueo fue tomado. |
| static [TryEnter](./tryenter/)(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) | Intenta, durante la cantidad de tiempo especificada, adquirir un bloqueo exclusivo en el objeto especificado y establece de forma atómica un valor que indica si el bloqueo fue tomado. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, int32_t, bool) | Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. Si transcurre el intervalo de tiempo de espera especificado, el hilo entra en la cola de preparados. Opcionalmente sale del dominio de sincronización para el contexto sincronizado antes de la espera y vuelve a adquirir el dominio después. No implementado. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, TimeSpan, bool) | Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. Si transcurre el intervalo de tiempo de espera especificado, el hilo entra en la cola de preparados. Opcionalmente sale del dominio de sincronización para el contexto sincronizado antes de la espera y vuelve a adquirir el dominio después. No implementado. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, int32_t) | Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. Si transcurre el intervalo de tiempo de espera especificado, el hilo entra en la cola de preparados. No implementado. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&, TimeSpan) | Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. Si transcurre el intervalo de tiempo de espera especificado, el hilo entra en la cola de preparados. No implementado. |
| static [Wait](./wait/)(const SharedPtr\<Object\>\&) | Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo No implementado. |
## Observaciones



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

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
