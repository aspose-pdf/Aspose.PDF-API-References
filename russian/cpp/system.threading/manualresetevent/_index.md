---
title: "System::Threading::ManualResetEvent класс"
linktitle: "ManualResetEvent"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::ManualResetEvent класс. Событие, которое уведомляет ожидающий поток и не сбрасывается автоматически. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 700
url: /ru/cpp/system.threading/manualresetevent/
---
## ManualResetEvent class


[Event](../../system/event/) to notify waiting thread that does not reset automatically. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ManualResetEvent : public System::Threading::EventWaitHandle
```

## Методы

| Метод | Описание |
| --- | --- |
| [ManualResetEvent](./manualresetevent/)(bool) | Информация RTTI. |
## Поля

| Поле | Описание |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Особое значение, которое возвращает функция; в остальных случаях возвращается индекс сигнального объекта в массиве, если время ожидания превышено и ничего не сигнализирует. |
## См. также

* Class [EventWaitHandle](../eventwaithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
