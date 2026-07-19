---
title: "System::Threading::Mutex class"
linktitle: "Mutex"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Mutex class. Реализация мьютекса. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 900
url: /ru/cpp/system.threading/mutex/
---
## Mutex class


[Mutex](./) implemnetation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Mutex : public System::Threading::WaitHandle
```

## Методы

| Метод | Описание |
| --- | --- |
| [Mutex](./mutex/)() | Информация RTTI. |
| [Mutex](./mutex/)(bool) | Конструктор. |
| [Mutex](./mutex/)(bool, const String\&) | Конструктор. |
| [ReleaseMutex](./releasemutex/)() | Освобождает мьютекс. |
| static [Remove](./remove/)(const String\&) | Удаляет именованный мьютекс из системы. |
| virtual [Reset](./reset/)() | Сбрасывает состояние мьютекса. Не реализовано. |
| virtual [Set](./set/)() | Устанавливает мьютекс в состояние сигнала. Не реализовано. |
| [WaitOne](./waitone/)() override | Блокирует мьютекс. При необходимости выполняет неограниченное ожидание. |
| [WaitOne](./waitone/)(int) override | Блокирует мьютекс. При необходимости выполняет ожидание. |
| [WaitOne](./waitone/)(TimeSpan) override | Блокирует мьютекс. При необходимости выполняет ожидание. |
## Поля

| Поле | Описание |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Особое значение, которое возвращает функция; в остальных случаях возвращается индекс сигнального объекта в массиве, если время ожидания превышено и ничего не сигнализирует. |
## Примечания



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

## См. также

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
