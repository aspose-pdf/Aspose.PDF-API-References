---
title: "Clase System::Threading::Thread"
linktitle: "Hilo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::Thread. Implementación del hilo. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.threading/thread/
---
## Thread class


[Thread](./) implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Thread : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Abort](./abort/)() | Abortar el hilo. No implementado. |
| [get_CurrentCulture](./get_currentculture/)() | Obtiene la cultura del hilo. |
| static [get_CurrentThread](./get_currentthread/)() | Obtiene el objeto que describe el hilo actual. |
| [get_CurrentUICulture](./get_currentuiculture/)() | Obtiene la cultura de la interfaz de usuario utilizada por el hilo. |
| [get_IsAlive](./get_isalive/)() | Comprueba si el hilo está activo. |
| [get_IsBackground](./get_isbackground/)() | Comprueba si el hilo es en segundo plano. |
| [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | Comprueba si el hilo es propiedad de un grupo de hilos. |
| [get_ManagedThreadId](./get_managedthreadid/)() const | Obtiene el identificador del hilo. Puede obtenerse del SO, pero si el identificador del hilo del SO supera los límites de int, los ids de los hilos pueden intersectarse. |
| [get_Name](./get_name/)() | Obtiene el nombre del hilo. |
| [get_ThreadState](./get_threadstate/)() | Obtiene el estado del hilo. |
| static [GetCurrentThreadId](./getcurrentthreadid/)() | Obtiene el identificador del hilo actual. |
| [GetHashCode](./gethashcode/)() const override |  |
| [Interrupt](./interrupt/)() | Interrumpir el hilo. No implementado. |
| [Join](./join/)() | Une el hilo gestionado. Realiza una espera ilimitada si es necesario. |
| [Join](./join/)(int) | Une el hilo gestionado. Realiza una espera limitada. |
| [Join](./join/)(TimeSpan) | Une el hilo gestionado. Realiza una espera limitada. |
| static [MemoryBarrier](./memorybarrier/)() | Sincroniza el acceso a la memoria. |
| [operator=](./operator=/)(const Thread\&) | Copia datos TLS de un hilo diferente. |
| [set_CurrentCulture](./set_currentculture/)(const SharedPtr\<Globalization::CultureInfo\>\&) | Establece la cultura del hilo. |
| [set_CurrentUICulture](./set_currentuiculture/)(const SharedPtr\<Globalization::CultureInfo\>\&) | Establece la cultura de la interfaz de usuario utilizada por el hilo. |
| [set_IsBackground](./set_isbackground/)(bool) | Establece el hilo como segundo plano o primer plano. |
| [set_Name](./set_name/)(const System::String\&) | Establece el nombre del hilo. |
| static [Sleep](./sleep/)(int) | Detiene el hilo actual durante el tiempo de espera especificado. |
| static [Sleep](./sleep/)(TimeSpan) | Detiene el hilo actual durante el tiempo de espera especificado. |
| static [SpinWait](./spinwait/)(int) | Espera un número específico de iteraciones del bucle. |
| [Start](./start/)() | Inicia el hilo usando un objeto de argumento nulo. |
| [Start](./start/)(const System::SharedPtr\<System::Object\>\&) | Inicia el hilo. |
| [Thread](./thread/)() | Constructor. |
| [Thread](./thread/)(ThreadStart) | Constructor. |
| [Thread](./thread/)(ParameterizedThreadStart) | Constructor. |
| [Thread](./thread/)(Thread\&) | Constructor de copia. |
| static [Yield](./yield/)() | Cede el hilo. |
| virtual [~Thread](./~thread/)() | Destructor. |
## Observaciones



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

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
