---
title: "System::Threading::WaitHandle класс"
linktitle: "WaitHandle"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::WaitHandle класс. Базовый класс примитивов ожидания. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1700
url: /ru/cpp/system.threading/waithandle/
---
## WaitHandle class


Базовый класс примитивов ожидания. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class WaitHandle : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Close](./close/)() | Освобождает любые ресурсы, связанные с дескриптором. |
| [get_Handle](./get_handle/)() | Получает дескриптор. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | Информация RTTI. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Ожидает срабатывания всех дескрипторов. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Ожидает срабатывания всех дескрипторов. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | Ожидает срабатывания любого из дескрипторов. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Ожидает срабатывания любого из дескрипторов. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Ожидает срабатывания любого из дескрипторов. |
| virtual [WaitOne](./waitone/)() | Ожидает срабатывания дескриптора бесконечно долго. |
| virtual [WaitOne](./waitone/)(int) | Ожидает срабатывания дескриптора. |
| virtual [WaitOne](./waitone/)(TimeSpan) | Ожидает срабатывания дескриптора. |
| virtual [WaitOne](./waitone/)(int, bool) | Ожидает срабатывания дескриптора. |
| virtual [~WaitHandle](./~waithandle/)() | Деструктор. |
## Поля

| Поле | Описание |
| --- | --- |
| static [WaitTimeout](./waittimeout/) | Особое значение, которое возвращает функция; в остальных случаях возвращается индекс сигнального объекта в массиве, если время ожидания превышено и ничего не сигнализирует. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
