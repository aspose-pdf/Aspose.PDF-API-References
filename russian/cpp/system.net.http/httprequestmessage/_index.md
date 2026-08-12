---
title: "System::Net::Http::HttpRequestMessage класс"
linktitle: "HttpRequestMessage"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::HttpRequestMessage класс. Представляет сообщение HTTP‑запроса. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 800
url: /ru/cpp/system.net.http/httprequestmessage/
---
## HttpRequestMessage class


Представляет сообщение HTTP‑запроса. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpRequestMessage : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Уничтожает текущий экземпляр. Этот метод также уничтожает содержимое HTTP‑запроса. |
| [get_Content](./get_content/)() | Получает содержимое HTTP‑запроса. |
| [get_Headers](./get_headers/)() | Возвращает заголовки содержимого HTTP. |
| [get_Method](./get_method/)() | Получает метод HTTP‑запроса. |
| [get_Properties](./get_properties/)() | Возвращает коллекцию свойств HTTP‑запроса. |
| [get_RequestUri](./get_requesturi/)() | Получает URI запрашиваемого ресурса. |
| [get_Version](./get_version/)() | Информация RTTI. |
| [HttpRequestMessage](./httprequestmessage/)() | Создаёт новый экземпляр. |
| [HttpRequestMessage](./httprequestmessage/)(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) | Создаёт новый экземпляр. |
| [HttpRequestMessage](./httprequestmessage/)(System::SharedPtr\<HttpMethod\>, String) | Создаёт новый экземпляр. |
| [MarkAsSent](./markassent/)() | Помечает текущий запрос как отправленный. |
| [set_Content](./set_content/)(System::SharedPtr\<HttpContent\>) | Устанавливает содержимое HTTP‑запроса. |
| [set_Method](./set_method/)(System::SharedPtr\<HttpMethod\>) | Устанавливает метод HTTP‑запроса. |
| [set_RequestUri](./set_requesturi/)(System::SharedPtr\<Uri\>) | Устанавливает URI запрашиваемого ресурса. |
| [set_Version](./set_version/)(System::Version) | Устанавливает версию HTTP. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
