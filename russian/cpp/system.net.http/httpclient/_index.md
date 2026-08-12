---
title: "System::Net::Http::HttpClient класс"
linktitle: "HttpClient"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::HttpClient класс. Представляет базовый класс HTTP‑клиента для отправки запросов и получения ответов. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.net.http/httpclient/
---
## HttpClient class


Представляет базовый класс HTTP‑клиента для отправки запросов и получения ответов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpClient : public System::Net::Http::HttpMessageInvoker
```

## Методы

| Метод | Описание |
| --- | --- |
| [CancelPendingRequests](./cancelpendingrequests/)() | Отменяет все ожидающие запросы. |
| [get_BaseAddress](./get_baseaddress/)() | Получает базовый адрес ресурса, используемого для отправки запросов. |
| [get_DefaultRequestHeaders](./get_defaultrequestheaders/)() | Информация RTTI. |
| [get_MaxResponseContentBufferSize](./get_maxresponsecontentbuffersize/)() | Получает максимальное количество байтов содержимого ответа. |
| [get_Timeout](./get_timeout/)() | Получает интервал ожидания до истечения времени запроса. |
| [HttpClient](./httpclient/)() | Создаёт новый экземпляр. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>) | Создаёт новый экземпляр. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Создаёт новый экземпляр. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) | Отправляет указанный HTTP‑запрос. |
| [set_BaseAddress](./set_baseaddress/)(System::SharedPtr\<Uri\>) | Устанавливает базовый адрес ресурса, используемого для отправки запросов. |
| [set_MaxResponseContentBufferSize](./set_maxresponsecontentbuffersize/)(int64_t) | Устанавливает максимальное количество байтов содержимого ответа. |
| [set_Timeout](./set_timeout/)(TimeSpan) | Устанавливает интервал ожидания до истечения времени запроса. |
## См. также

* Class [HttpMessageInvoker](../httpmessageinvoker/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
