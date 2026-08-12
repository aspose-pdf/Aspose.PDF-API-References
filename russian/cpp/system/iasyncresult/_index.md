---
title: "System::IAsyncResult class"
linktitle: "IAsyncResult"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::IAsyncResult. Представляет статус асинхронной операции. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3200
url: /ru/cpp/system/iasyncresult/
---
## IAsyncResult class


Представляет статус асинхронной операции. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class IAsyncResult : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_AsyncState](./get_asyncstate/)() | Возвращает объект, содержащий информацию об асинхронной операции. |
| virtual [get_AsyncWaitHandle](./get_asyncwaithandle/)() | Возвращает экземпляр WaitHandle, который можно использовать для ожидания завершения асинхронной операции. |
| virtual [get_CompletedSynchronously](./get_completedsynchronously/)() | Возвращает значение, указывающее, завершилась ли асинхронная операция синхронно. |
| virtual [get_IsCompleted](./get_iscompleted/)() | Возвращает значение, указывающее, завершилась ли асинхронная операция. |
| virtual [~IAsyncResult](./~iasyncresult/)() | Деструктор. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [smart_ptr](./smart_ptr/) | Умный указатель на [IAsyncResult](./). |
## См. также

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
