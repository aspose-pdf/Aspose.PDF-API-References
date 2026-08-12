---
title: "System::Threading::Semaphore class"
linktitle: "Semaphore"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Semaphore class. Реализация семафора. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1000
url: /ru/cpp/system.threading/semaphore/
---
## Semaphore class


[Semaphore](./) implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Semaphore : public System::Threading::WaitHandle
```

## Методы

| Метод | Описание |
| --- | --- |
| [Release](./release/)() | Снимает блокировку с семафора. |
| [Release](./release/)(int) | Снимает несколько блокировок с семафора. |
| virtual [Reset](./reset/)() | Устанавливает семафор в состояние без сигнала. Не поддерживается. |
| [Semaphore](./semaphore/)(int, int) | Информация RTTI. |
| [Semaphore](./semaphore/)(int, int, const String\&) | Создаёт именованный семафор. |
| [Semaphore](./semaphore/)(int, int, const String\&, bool\&) | Создаёт именованный семафор. |
| virtual [Set](./set/)() | Устанавливает семафор в состояние с сигналом. Не поддерживается. |
| [WaitOne](./waitone/)() override | Блокирует семафор. Выполняет неограниченное ожидание, если необходимо. |
| [WaitOne](./waitone/)(int) override | Блокирует семафор. Выполняет ожидание, если необходимо. |
## Поля

| Поле | Описание |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Особое значение, которое возвращает функция; в остальных случаях возвращается индекс сигнального объекта в массиве, если время ожидания превышено и ничего не сигнализирует. |
## См. также

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
