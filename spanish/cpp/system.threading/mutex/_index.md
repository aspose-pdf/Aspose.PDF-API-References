---
title: "Clase System::Threading::Mutex"
linktitle: "Mutex"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::Mutex. Implementación de Mutex. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.threading/mutex/
---
## Mutex class


[Mutex](./) implemnetation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Mutex : public System::Threading::WaitHandle
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Mutex](./mutex/)() | Información RTTI. |
| [Mutex](./mutex/)(bool) | Constructor. |
| [Mutex](./mutex/)(bool, const String\&) | Constructor. |
| [ReleaseMutex](./releasemutex/)() | Libera el mutex. |
| static [Remove](./remove/)(const String\&) | Elimina un mutex con nombre del sistema. |
| virtual [Reset](./reset/)() | Restablece el estado del mutex. No implementado. |
| virtual [Set](./set/)() | Establece el mutex en estado señalizado. No implementado. |
| [WaitOne](./waitone/)() override | Bloquea el mutex. Realiza una espera ilimitada si es necesario. |
| [WaitOne](./waitone/)(int) override | Bloquea el mutex. Realiza una espera si es necesario. |
| [WaitOne](./waitone/)(TimeSpan) override | Bloquea el mutex. Realiza una espera si es necesario. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Valor especial que debe ser devuelto por la función, de lo contrario se devuelve el índice del objeto señalizado en el arreglo, si el tiempo de espera se supera y nada señala. |
## Observaciones



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

## Ver también

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
