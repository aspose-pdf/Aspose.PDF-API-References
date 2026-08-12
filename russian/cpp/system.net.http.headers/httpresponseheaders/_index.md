---
title: "System::Net::Http::Headers::HttpResponseHeaders класс"
linktitle: "HttpResponseHeaders"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::HttpResponseHeaders класс. Представляет коллекцию заголовков ''Response''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1100
url: /ru/cpp/system.net.http.headers/httpresponseheaders/
---
## HttpResponseHeaders class


Представляет коллекцию заголовков 'Response'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpResponseHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) override | Объединяет указанный экземпляр класса HttpHeaders с текущим. |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Добавляет известные заголовки в указанную коллекцию. |
| [get_AcceptRanges](./get_acceptranges/)() | Информация RTTI. |
| [get_Age](./get_age/)() | Получает значение заголовка 'Age'. |
| [get_CacheControl](./get_cachecontrol/)() | Получает значение заголовка 'Cache-Control'. |
| [get_Connection](./get_connection/)() | Возвращает значение заголовка 'Connection'. |
| [get_ConnectionClose](./get_connectionclose/)() | Получает значение, указывающее, содержит ли значение заголовка 'Connection' строку 'Close'. |
| [get_Date](./get_date/)() | Получает значение заголовка 'Date'. |
| [get_ETag](./get_etag/)() | Получает значение заголовка 'ETag'. |
| [get_Location](./get_location/)() | Получает значение заголовка 'Location'. |
| [get_Pragma](./get_pragma/)() | Возвращает значение заголовка 'Pragma'. |
| [get_ProxyAuthenticate](./get_proxyauthenticate/)() | Возвращает значение заголовка 'Proxy-Authenticate'. |
| [get_RetryAfter](./get_retryafter/)() | Получает значение заголовка 'Retry-After'. |
| [get_Server](./get_server/)() | Возвращает значение заголовка 'Server'. |
| [get_Trailer](./get_trailer/)() | Возвращает значение заголовка 'Trailer'. |
| [get_TransferEncoding](./get_transferencoding/)() | Возвращает значение заголовка 'Transfer-Encoding'. |
| [get_TransferEncodingChunked](./get_transferencodingchunked/)() | Получает значение, указывающее, содержит ли значение заголовка 'Transfer-Encoding' 'Chunked'. |
| [get_Upgrade](./get_upgrade/)() | Возвращает значение заголовка 'Upgrade'. |
| [get_Vary](./get_vary/)() | Возвращает значение заголовка 'Vary'. |
| [get_Via](./get_via/)() | Возвращает значение заголовка 'Via'. |
| [get_Warning](./get_warning/)() | Возвращает значение заголовка 'Warning'. |
| [get_WwwAuthenticate](./get_wwwauthenticate/)() | Возвращает значение заголовка 'WWW-Authenticate'. |
| [HttpResponseHeaders](./httpresponseheaders/)() | Создаёт новый экземпляр. |
| [set_Age](./set_age/)(Nullable\<TimeSpan\>) | Устанавливает значение заголовка 'Age'. |
| [set_CacheControl](./set_cachecontrol/)(System::SharedPtr\<CacheControlHeaderValue\>) | Устанавливает значение заголовка 'Cache-Control'. |
| [set_ConnectionClose](./set_connectionclose/)(Nullable\<bool\>) | Устанавливает значение, указывающее, содержит ли значение заголовка 'Connection' 'Close'. |
| [set_Date](./set_date/)(Nullable\<DateTimeOffset\>) | Устанавливает значение заголовка 'Date'. |
| [set_ETag](./set_etag/)(System::SharedPtr\<EntityTagHeaderValue\>) | Устанавливает значение заголовка 'ETag'. |
| [set_Location](./set_location/)(System::SharedPtr\<Uri\>) | Устанавливает значение заголовка 'Location'. |
| [set_RetryAfter](./set_retryafter/)(System::SharedPtr\<RetryConditionHeaderValue\>) | Устанавливает значение заголовка 'Retry-After'. |
| [set_TransferEncodingChunked](./set_transferencodingchunked/)(Nullable\<bool\>) | Устанавливает значение, указывающее, содержит ли значение заголовка 'Transfer-Encoding' 'Chunked'. |
## См. также

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
