---
title: "Класс System::Threading::EventWaitHandle"
linktitle: "EventWaitHandle"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Threading::EventWaitHandle. Событие, которое может быть отправлено ожидающему потоку. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.threading/eventwaithandle/
---
## EventWaitHandle class


[Event](../../system/event/) that can be sent to waiting thread. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EventWaitHandle : public System::Threading::WaitHandle
```

## Методы

| Метод | Описание |
| --- | --- |
| [EventWaitHandle](./eventwaithandle/)(bool, EventResetMode) | Информация RTTI. |
| virtual [Reset](./reset/)() | Устанавливает событие в состояние без сигнала. |
| virtual [Set](./set/)() | Устанавливает событие в состояние с сигналом. |
| [~EventWaitHandle](./~eventwaithandle/)() | Деструктор. |
## Поля

| Поле | Описание |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Особое значение, которое возвращает функция; в остальных случаях возвращается индекс сигнального объекта в массиве, если время ожидания превышено и ничего не сигнализирует. |
## См. также

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
