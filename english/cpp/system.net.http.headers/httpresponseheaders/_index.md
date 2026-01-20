---
title: System::Net::Http::Headers::HttpResponseHeaders class
linktitle: HttpResponseHeaders
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::HttpResponseHeaders class. Represents the collection of the ''Response'' headers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.net.http.headers/httpresponseheaders/
---
## HttpResponseHeaders class


Represents the collection of the 'Response' headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpResponseHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Methods

| Method | Description |
| --- | --- |
| [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) override | Concatenates the specified HttpHeaders-class instance with the current one. |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Adds the known headers to the specified collection. |
| [get_AcceptRanges](./get_acceptranges/)() | RTTI information. |
| [get_Age](./get_age/)() | Gets a value of the 'Age' header. |
| [get_CacheControl](./get_cachecontrol/)() | Gets a value of the 'Cache-Control' header. |
| [get_Connection](./get_connection/)() | Returns a value of the 'Connection' header. |
| [get_ConnectionClose](./get_connectionclose/)() | Gets a value that indicates if the 'Connection' header value contains 'Close'. |
| [get_Date](./get_date/)() | Gets a value of the 'Date' header. |
| [get_ETag](./get_etag/)() | Gets a value of the 'ETag' header. |
| [get_Location](./get_location/)() | Gets a value of the 'Location' header. |
| [get_Pragma](./get_pragma/)() | Returns a value of the 'Pragma' header. |
| [get_ProxyAuthenticate](./get_proxyauthenticate/)() | Returns a value of the 'Proxy-Authenticate' header. |
| [get_RetryAfter](./get_retryafter/)() | Gets a value of the 'Retry-After' header. |
| [get_Server](./get_server/)() | Returns a value of the 'Server' header. |
| [get_Trailer](./get_trailer/)() | Returns a value of the 'Trailer' header. |
| [get_TransferEncoding](./get_transferencoding/)() | Returns a value of the 'Transfer-Encoding' header. |
| [get_TransferEncodingChunked](./get_transferencodingchunked/)() | Gets a value that indicates if the 'Transfer-Encoding' header value contains 'Chunked'. |
| [get_Upgrade](./get_upgrade/)() | Returns a value of the 'Upgrade' header. |
| [get_Vary](./get_vary/)() | Returns a value of the 'Vary' header. |
| [get_Via](./get_via/)() | Returns a value of the 'Via' header. |
| [get_Warning](./get_warning/)() | Returns a value of the 'Warning' header. |
| [get_WwwAuthenticate](./get_wwwauthenticate/)() | Returns a value of the 'WWW-Authenticate' header. |
| [HttpResponseHeaders](./httpresponseheaders/)() | Constructs a new instance. |
| [set_Age](./set_age/)(Nullable\<TimeSpan\>) | Sets a value of the 'Age' header. |
| [set_CacheControl](./set_cachecontrol/)(System::SharedPtr\<CacheControlHeaderValue\>) | Sets a value of the 'Cache-Control' header. |
| [set_ConnectionClose](./set_connectionclose/)(Nullable\<bool\>) | Sets a value that indicates if the 'Connection' header value contains 'Close'. |
| [set_Date](./set_date/)(Nullable\<DateTimeOffset\>) | Sets a value of the 'Date' header. |
| [set_ETag](./set_etag/)(System::SharedPtr\<EntityTagHeaderValue\>) | Sets a value of the 'ETag' header. |
| [set_Location](./set_location/)(System::SharedPtr\<Uri\>) | Sets a value of the 'Location' header. |
| [set_RetryAfter](./set_retryafter/)(System::SharedPtr\<RetryConditionHeaderValue\>) | Sets a value of the 'Retry-After' header. |
| [set_TransferEncodingChunked](./set_transferencodingchunked/)(Nullable\<bool\>) | Sets a value that indicates if the 'Transfer-Encoding' header value contains 'Chunked'. |
## See Also

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
