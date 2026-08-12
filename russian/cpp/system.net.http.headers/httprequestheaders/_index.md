---
title: "Класс System::Net::Http::Headers::HttpRequestHeaders"
linktitle: "HttpRequestHeaders"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::Http::Headers::HttpRequestHeaders. Представляет коллекцию заголовков ''Request''. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1000
url: /ru/cpp/system.net.http.headers/httprequestheaders/
---
## HttpRequestHeaders class


Представляет коллекцию заголовков 'Request'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpRequestHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) override | Объединяет указанный экземпляр класса HttpHeaders с текущим. |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Добавляет известные заголовки в указанную коллекцию. |
| [get_Accept](./get_accept/)() | Информация RTTI. |
| [get_AcceptCharset](./get_acceptcharset/)() | Возвращает значение заголовка 'Accept-Charset'. |
| [get_AcceptEncoding](./get_acceptencoding/)() | Возвращает значение заголовка 'Accept-Encoding'. |
| [get_AcceptLanguage](./get_acceptlanguage/)() | Возвращает значение заголовка 'Accept-Language'. |
| [get_Authorization](./get_authorization/)() | Получает значение заголовка 'Authorization'. |
| [get_CacheControl](./get_cachecontrol/)() | Получает значение заголовка 'Cache-Control'. |
| [get_Connection](./get_connection/)() | Возвращает значение заголовка 'Connection'. |
| [get_ConnectionClose](./get_connectionclose/)() | Получает значение, указывающее, содержит ли значение заголовка 'Connection' строку 'Close'. |
| [get_Date](./get_date/)() | Получает значение заголовка 'Date'. |
| [get_Expect](./get_expect/)() | Возвращает значение заголовка 'Expect'. |
| [get_ExpectContinue](./get_expectcontinue/)() | Получает значение, указывающее, содержит ли значение заголовка 'Expect' строку 'Continue'. |
| [get_From](./get_from/)() | Получает значение заголовка 'From'. |
| [get_Host](./get_host/)() | Получает значение заголовка 'Host'. |
| [get_IfMatch](./get_ifmatch/)() | Возвращает значение заголовка 'If-Match'. |
| [get_IfModifiedSince](./get_ifmodifiedsince/)() | Получает значение заголовка 'If-Modified-Since'. |
| [get_IfNoneMatch](./get_ifnonematch/)() | Возвращает значение заголовка 'If-None-Match'. |
| [get_IfRange](./get_ifrange/)() | Получает значение заголовка 'If-Range'. |
| [get_IfUnmodifiedSince](./get_ifunmodifiedsince/)() | Получает значение заголовка 'If-Unmodified-Since'. |
| [get_MaxForwards](./get_maxforwards/)() | Получает значение заголовка 'Max-Forwards'. |
| [get_Pragma](./get_pragma/)() | Возвращает значение заголовка 'Pragma'. |
| [get_ProxyAuthorization](./get_proxyauthorization/)() | Получает значение заголовка 'Proxy-Authorization'. |
| [get_Range](./get_range/)() | Получает значение заголовка '[Range](../../system/range/)'. |
| [get_Referrer](./get_referrer/)() | Получает значение заголовка 'Referer'. |
| [get_TE](./get_te/)() | Возвращает значение заголовка 'TE'. |
| [get_Trailer](./get_trailer/)() | Возвращает значение заголовка 'Trailer'. |
| [get_TransferEncoding](./get_transferencoding/)() | Возвращает значение заголовка 'Transfer-Encoding'. |
| [get_TransferEncodingChunked](./get_transferencodingchunked/)() | Получает значение, указывающее, содержит ли значение заголовка 'Transfer-Encoding' 'Chunked'. |
| [get_Upgrade](./get_upgrade/)() | Возвращает значение заголовка 'Upgrade'. |
| [get_UserAgent](./get_useragent/)() | Возвращает значение заголовка 'User-Agent'. |
| [get_Via](./get_via/)() | Возвращает значение заголовка 'Via'. |
| [get_Warning](./get_warning/)() | Возвращает значение заголовка 'Warning'. |
| [HttpRequestHeaders](./httprequestheaders/)() | Создаёт новый экземпляр. |
| [set_Authorization](./set_authorization/)(System::SharedPtr\<AuthenticationHeaderValue\>) | Устанавливает значение заголовка 'Authorization'. |
| [set_CacheControl](./set_cachecontrol/)(System::SharedPtr\<CacheControlHeaderValue\>) | Устанавливает значение заголовка 'Cache-Control'. |
| [set_ConnectionClose](./set_connectionclose/)(Nullable\<bool\>) | Устанавливает значение, указывающее, содержит ли значение заголовка 'Connection' 'Close'. |
| [set_Date](./set_date/)(Nullable\<DateTimeOffset\>) | Устанавливает значение заголовка 'Date'. |
| [set_ExpectContinue](./set_expectcontinue/)(Nullable\<bool\>) | Устанавливает значение, указывающее, содержит ли значение заголовка 'Expect' 'Continue'. |
| [set_From](./set_from/)(String) | Устанавливает значение заголовка 'From'. |
| [set_Host](./set_host/)(String) | Устанавливает значение заголовка 'Host'. |
| [set_IfModifiedSince](./set_ifmodifiedsince/)(Nullable\<DateTimeOffset\>) | Устанавливает значение заголовка 'If-Modified-Since'. |
| [set_IfRange](./set_ifrange/)(System::SharedPtr\<RangeConditionHeaderValue\>) | Устанавливает значение заголовка 'If-Range'. |
| [set_IfUnmodifiedSince](./set_ifunmodifiedsince/)(Nullable\<DateTimeOffset\>) | Устанавливает значение заголовка 'If-Unmodified-Since'. |
| [set_MaxForwards](./set_maxforwards/)(Nullable\<int32_t\>) | Устанавливает значение заголовка 'Max-Forwards'. |
| [set_ProxyAuthorization](./set_proxyauthorization/)(System::SharedPtr\<AuthenticationHeaderValue\>) | Устанавливает значение заголовка 'Proxy-Authorization'. |
| [set_Range](./set_range/)(System::SharedPtr\<RangeHeaderValue\>) | Устанавливает значение заголовка '[Range](../../system/range/)'. |
| [set_Referrer](./set_referrer/)(System::SharedPtr\<Uri\>) | Устанавливает значение заголовка 'Referer'. |
| [set_TransferEncodingChunked](./set_transferencodingchunked/)(Nullable\<bool\>) | Устанавливает значение, указывающее, содержит ли значение заголовка 'Transfer-Encoding' 'Chunked'. |
## См. также

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
