---
title: "System::Threading::Thread класс"
linktitle: "Поток"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Thread класс. Реализация потока. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1200
url: /ru/cpp/system.threading/thread/
---
## Thread class


[Thread](./) implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Thread : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Abort](./abort/)() | Прерывает поток. Не реализовано. |
| [get_CurrentCulture](./get_currentculture/)() | Получает культуру потока. |
| static [get_CurrentThread](./get_currentthread/)() | Получает объект, описывающий текущий поток. |
| [get_CurrentUICulture](./get_currentuiculture/)() | Получает культуру пользовательского интерфейса, используемую потоком. |
| [get_IsAlive](./get_isalive/)() | Проверяет, жив ли поток. |
| [get_IsBackground](./get_isbackground/)() | Проверяет, является ли поток фоновым. |
| [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | Проверяет, принадлежит ли поток пулу потоков. |
| [get_ManagedThreadId](./get_managedthreadid/)() const | Получает идентификатор потока. Может быть получен из ОС, но если идентификатор потока ОС превышает пределы int, идентификаторы потоков могут пересекаться. |
| [get_Name](./get_name/)() | Получает имя потока. |
| [get_ThreadState](./get_threadstate/)() | Получает состояние потока. |
| static [GetCurrentThreadId](./getcurrentthreadid/)() | Получает идентификатор текущего потока. |
| [GetHashCode](./gethashcode/)() const override |  |
| [Interrupt](./interrupt/)() | Прерывает поток. Не реализовано. |
| [Join](./join/)() | Ожидает завершения управляемого потока. Выполняет неограниченное ожидание при необходимости. |
| [Join](./join/)(int) | Ожидает завершения управляемого потока. Выполняет ограниченное ожидание. |
| [Join](./join/)(TimeSpan) | Ожидает завершения управляемого потока. Выполняет ограниченное ожидание. |
| static [MemoryBarrier](./memorybarrier/)() | Синхронизирует доступ к памяти. |
| [operator=](./operator=/)(const Thread\&) | Копирует данные TLS из другого потока. |
| [set_CurrentCulture](./set_currentculture/)(const SharedPtr\<Globalization::CultureInfo\>\&) | Устанавливает культуру потока. |
| [set_CurrentUICulture](./set_currentuiculture/)(const SharedPtr\<Globalization::CultureInfo\>\&) | Устанавливает культуру пользовательского интерфейса, используемую потоком. |
| [set_IsBackground](./set_isbackground/)(bool) | Устанавливает поток в фоновый или передний режим. |
| [set_Name](./set_name/)(const System::String\&) | Устанавливает имя потока. |
| static [Sleep](./sleep/)(int) | Останавливает текущий поток на указанный тайм-аут. |
| static [Sleep](./sleep/)(TimeSpan) | Останавливает текущий поток на указанный тайм-аут. |
| static [SpinWait](./spinwait/)(int) | Ожидает определённое количество итераций цикла. |
| [Start](./start/)() | Запускает поток, используя объект нулевого аргумента. |
| [Start](./start/)(const System::SharedPtr\<System::Object\>\&) | Запускает поток. |
| [Thread](./thread/)() | Конструктор. |
| [Thread](./thread/)(ThreadStart) | Конструктор. |
| [Thread](./thread/)(ParameterizedThreadStart) | Конструктор. |
| [Thread](./thread/)(Thread\&) | Конструктор копирования. |
| static [Yield](./yield/)() | Передаёт управление потоку. |
| virtual [~Thread](./~thread/)() | Деструктор. |
## Примечания



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

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
