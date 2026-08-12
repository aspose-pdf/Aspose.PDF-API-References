---
title: "Класс System::Net::Http::HttpResponseMessage"
linktitle: "HttpResponseMessage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::Http::HttpResponseMessage. Представляет сообщение HTTP-ответа. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 900
url: /ru/cpp/system.net.http/httpresponsemessage/
---
## HttpResponseMessage class


Представляет сообщение HTTP-ответа. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpResponseMessage : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Освобождает текущий экземпляр. Этот метод также освобождает содержимое HTTP-ответа. |
| [EnsureSuccessStatusCode](./ensuresuccessstatuscode/)() | Проверяет код состояния. Будет выброшено исключение [HttpRequestException](../httprequestexception/), если код состояния не относится к диапазону 2xx. |
| [get_Content](./get_content/)() const | Получает содержимое HTTP-ответа. |
| [get_Headers](./get_headers/)() const | Возвращает заголовки содержимого HTTP. |
| [get_IsSuccessStatusCode](./get_issuccessstatuscode/)() const | Проверяет, указывает ли код состояния, что действие, запрошенное клиентом, было получено, понято и принято. |
| [get_ReasonPhrase](./get_reasonphrase/)() const | Получает Reason-Phrase, отправляемый серверами вместе с кодом состояния. |
| [get_RequestMessage](./get_requestmessage/)() const | Получает сообщение HTTP-запроса. |
| [get_StatusCode](./get_statuscode/)() const | Получает код состояния HTTP. |
| [get_Version](./get_version/)() const | Информация RTTI. |
| [HttpResponseMessage](./httpresponsemessage/)() | Создаёт новый экземпляр. |
| [HttpResponseMessage](./httpresponsemessage/)(HttpStatusCode) | Создаёт новый экземпляр. |
| [set_Content](./set_content/)(System::SharedPtr\<HttpContent\>) | Устанавливает содержимое HTTP-ответа. |
| [set_ReasonPhrase](./set_reasonphrase/)(String) | Устанавливает Reason-Phrase, отправляемый серверами вместе с кодом состояния. |
| [set_RequestMessage](./set_requestmessage/)(System::SharedPtr\<HttpRequestMessage\>) | Устанавливает сообщение HTTP-запроса. |
| [set_StatusCode](./set_statuscode/)(HttpStatusCode) | Устанавливает код состояния HTTP. |
| [set_Version](./set_version/)(System::Version) | Устанавливает версию HTTP. |
| [ToString](./tostring/)() const override | [System::Object::ToString](../../system/object/tostring/). |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
