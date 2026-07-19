---
title: "System::Net::Http::HttpMessageInvoker класс"
linktitle: "HttpMessageInvoker"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::HttpMessageInvoker класс. Позволяет приложениям вызывать метод Send в цепочке обработчиков HTTP. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.net.http/httpmessageinvoker/
---
## HttpMessageInvoker class


Позволяет приложениям вызывать метод Send в цепочке обработчиков HTTP. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpMessageInvoker : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Освобождает текущий экземпляр. Этот метод также освобождает обработчик, если это необходимо. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>) | Информация RTTI. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Создаёт новый экземпляр. |
| virtual [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) | Отправляет указанный запрос. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
